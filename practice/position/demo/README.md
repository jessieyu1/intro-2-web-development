# CSS position

## Learning Objectives

All five CSS positions

- How absolute position interacts with the other positions
- How to use top/right/left/bottom to position elements
- How the document flow works
- When to use relative position

## Task

- 5 positions:
  1. static: default
  2. relative: relative to static || But lets you add top, right, bottom, left. Makes it move relative to it's normal position
  3. absolute: Removes from the flow and positions absolute wrt to the parent. Parent has to be relative or absolute for top, right, bottom, left to work. Else it considers the main html element as the parent. move when you scroll
  4. fixed: Fixed to a place. Doesn't care about the parent. Always considers html element as the parent. Stays there when scrolled.
  5. sticky: Relative ( when normal) + fixed ( when scrolled). The values for top, right, bottom, left become active when scrolled
