* Why?
  - Spaghetti CSS
  - CSS Bloat
  - Breaking the Cascade (Over-specificity)
* A Quick Review
  - Box Model/Box Sizing
  - Specificity
* Layout Techniques
  - Floating
    - Pros: Cross-browser support
    - Cons: Clearfix, clearfix can have unintended consequences
  - Display Inline (Columns?)
    - Pros: Cleaner markup, no clearfix
    - Cons: Whitespace is significant
  - Absolute Positioning (Centering, Dropdown)
    - Pros: Precise control, breaks flow
    - Cons: Z-index issues
* The Approach
  - Laying out on a grid
  - Building modules (refactor previous examples)
    - Style based on classes, not markup
    - Separate structure and chrome
* Application
