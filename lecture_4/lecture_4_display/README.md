# Display 
The *display* property determines **how an element is displayed** in a document flow- how it behaves in relation to surrounding elements.
The three most common display types are:
1. Block Elements
Default behavior: Takes up the full width of its container, forcing content after it to start on a new line.

Examples of block elements:
div, p , h1 to h6, section , article

Charactersistics :
starts on a new line, can have width, height, margin , padding, border, fills the width of the parent container by default.

2. Inline elements
Default behavior: Takes up only as much width as its content and does not start on a new line.

Examples of inline elements:
span , a , strong, em

Characteristics:
 Stays in the flow with text, cannot set width or height, can use horizontal padding, margin , but vertical spacing is limited

3. Inline - block
Hybrid behavior: Behaves like an inline element (stays on the same line), but you can apply width, height, padding, and margin like a block element.

Characteristics:
Sits inline next to other elements, allows full box model styling(width, height, margin , padding), great for buttons, nav items and layout blocks


# Position : Absolute 
The position absolute property removes an element from the normal document flow and **positions it relative to the nearest possitioned ancestor(and elment with position: relative, absolute, or fixed)**
if no such ancestor exits, it will position relative to the html or body element

 Key Characteristics:
 Out of flow: The element is removed from the normal layout flow. It doesn't affect or get affected by nearby elements.
 Stacking: It can overlap other elements.
 Requires coordinates: Use top, right, bottom, and left to define position.
 Parent dependency: It positions relative to the first ancestor that has position: relative, absolute, or fixed.


 # Position: Relative
 It means the element is positioned relative to its normal position in the document flow.

 This **does not remove the element from the flow** - it still takes up space as if it were in its default position - but you can offset if using **top, right, bottom , left.**
 
  