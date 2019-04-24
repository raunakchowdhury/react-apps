# ReactJS Workshop
- Problems with traditional frontend
  - Lack of encapsulation: JS by nature is global and so is CSS
    - CSS files dump classes into the global namespace which can result in namespace conflicts
  - Lack of reusability
    - Can reuse HTML templates, but what about reusable semantics?
  - Difficulty updating UI
    - JS can update any part of the DOM

- Solutions: Components, one way data flow, virtual DOM
  - Components: little UI widgets
    - Can render each other
  - One way data flow: can bring data down and not bring it down
    - Can update by looking at data pushed downward
  - Virtual DOM
    - One way data flow enables allows for anticipation for changes within the DOM

## Callback functions
- Once you pass data down to a Component, you can't get it back
  - You can ask Components to do actions via *callbacks*
  - Callback functions should be defined in App.js and applied to components in the Component file
