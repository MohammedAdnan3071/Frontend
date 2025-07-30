# Pseudo-Elements

Pseudo-Elements allow you to style specific parts of an element or insert content without modifying the HTML.

1. ::before 
Description: Inserts content before the actual content of the element.
    p::before {
  content: "Note: ";
  color: red;
    }

2. ::after
Description: Inserts content after the actual content of the element.
  p::after {
  content: " ✔";
  color: green;
}

3. ::first-line
 Description: Styles the first line of text in a block element.
    p::first-line {
  font-weight: bold;
  color: blue;
}

4. ::first-letter
Description: Styles the first letter of the first line of text in a block element.
 p::first-letter {
  font-size: 200%;
  color: darkred;
}

5. ::selection
Description: Styles the portion of text selected by the user.
::selection {
  background: yellow;
  color: black;
}
<br/>

# Pseudo-Classes
Pseudo-classes define the state of an element or allow targeting elements based on conditions.

1. :hover
Description: Applies styles when the user hovers over an element with a mouse.
 a:hover {
  color: red;
  text-decoration: underline;
}


2. :acitve
Description: Applies styles when an element is being clicked or activated.
 button:active {
  background-color: darkblue;
}

3. :focus
Description: Applies styles when an element (usually input or button) gains focus (e.g., clicked or tabbed into).
input:focus {
  border-color: blue;
  outline: none;
}

4. :nth-child(n)
Description: Targets the nth child of a parent, where n can be a number or formula.