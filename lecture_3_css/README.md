# Introduction to CSS

## Color in Css
CSS allows you to define the color of text, backgrounds, borders, and other elements using several formats.
1. Named Colors : red, blue, black etc 
2. Hex colors : #FF0000 
3. RGB / RGBA : rgb(255, 0, 0)  or rgba(255, 0, 0, 0.5)
4. HSL / HSLA : hsl(102,100%,50%)

## Font Family in CSS
The font-family property defines which typeface is used for the text 
font-family: 'Arial', 'Helvetica', sans-serif;
 You can list multiple fonts as fallbacks


## Weights and Heights in CSS
These are often used to style text and layout 

### Font weight
Controls the thickness of the text :

font-weight: normal;     /* Equivalent to 400 */
font-weight: bold;       /* Equivalent to 700 */
font-weight: 100–900;    /* Numeric scale */

### Font Height
Can refer to :
1. Line Height (Spacing between lines of text):
  line-height:1.5;
2. Element Height:
   height : 200px;

## Units in CSS
Units define the size of the properties like **marign,** **padding,** **width,** **height,** **font-size etc**

## Units

### Pixels - px
absolute unit.
what it does :Represents a fixed number of screen pixels.
Use case: Precise control, useful for borders, icons, etc.
   div{
    width : 200px;
   }

### Percentage - %
Relative unit.
what it does:Relative to the parent element's dimensions.
Use case: Flexible layouts that adapt to containter size.
    div{
      width : 50%
    }

### vh and vw - Viewport Units
Relative type
What it does : 
    1vh = 1% of viewport height
    1vw = 1% of viewport width
Use case :
 Fullscreen sections, responsive typography, etc 


### em 
Relative type
What it does: Relative to the font size of the parent element.
Use case: Scalable spacing, padding etc that respects user font size settings.
           div{
            font-size : 1.5em;
           }

### rem - Root em
Relative type
What it does : Relative to the root element's font size
use case : Consistent typography across components.

  html{
    font-size:16px;
  }
 p{
  font-size: 1.5rem ; // 1.5rem = 1.5 * 16 = 24px;
 }