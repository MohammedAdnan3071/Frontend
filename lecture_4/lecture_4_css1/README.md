# Padding
Padding controls the **space inside an element**, between its content and its border.

when you apply padding, you are pushing the content inward, creating internal breathing room. 
Padding can be applied to all four sides :
1. top
2. right
3. bottom
4. left

if the element has a background color or border, the padding area is included within it .

 .box {
  padding-top: 10px;
  padding-right: 15px;
  padding-bottom: 10px;
  padding-left: 15px;
}

# Margin 
Margin controls the sapce outside an element, separating it from other elements on the page.

Margins are used to create spacing between elements like divs, headings, paragraphs etc

Margins are always transparent and can collapse vertically when adjacent blocks both have vertical margins - this is known as **margin collapsing**

.box {
  margin-top: 20px;
  margin-bottom: 20px;
}


# Border
The border property adds a visible outline around an HTML element.
It sits between the element's padding and its margin in the css box model

A border can have width, style, and color, and can be applied to all sides or specific sides (top, right, bottom, left)

element {
  border: 2px solid black;
}
