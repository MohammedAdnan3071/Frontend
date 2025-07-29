# Lecture 1 : HTML Tags and Attributes

## HTML Tags
Tags are used to create elements in an HTML page.
They usually come in pairs: an opening tag and a closing tag.

<p> This is a paragraph </p>

<p> is the opening tag.
</p> is the closing tag.
The content between them is shown on the webpage.
<br/>
## HTML Attributes
Attrbites give **extra information** about an element.
They are written **inside the opening tag.**

<a href="https://example.com">Visit Site</a>

<a> is a tag
href = "https://example.com" is an attribute that tells where the link goes
<br/>

## <sup> Tag – Superscript
The <sup> tag is used to show **superscript** text.
Superscript text appears above the normal line.

X<sup>2</sup>
Output: X²
Used for:
Math expressions (e.g., x²)
Footnotes (e.g., text<sup>1</sup>)

<br/>

## <sub> Tag – Subscript
The <sub> tag is used to show subscript text.
Subscript text appears below the normal line.

H<sub>2</sub>O
Output: H₂O
Used for:
Chemical formulas (e.g., H₂O)
Math or technical writing

<br/>

## <hr> – Horizontal Line
Creates a horizontal line across the page
Used to separate content
No closing tag

Paragraph 1<hr>Paragraph 2

<br/>

## <ol> – Ordered List
Creates a numbered list.
Items go inside <li> tags.
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>

<br/>

##  <ul> – Unordered List
Created a bulleted lists
Also uses <li> for items
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>
<br/>

##  Forms
An HTML form is used to collect user input.
It can include text boxes, radio buttons, checkboxes, dropdowns, and more.
The form sends data to a server when the user clicks **Submit**

## label
The **label** tag is used to name or describe an input field.
It improves accessibility and makes forms easier to use
 ### What is for in label ?
 The for attribute connects the label to a specific input field.
It should match the id of the input element.
####  Why is it useful?
When you click the label, the matching input field gets focused (selected).
This makes the form easier to use and more accessible.

## Radio 
A radio button lets users select only one option from a group.
Used in forms when one choice is allowed (like gender, payment method, etc.).

##  What is <input type="file">?
 It allows the user to upload a file from their device (like an image, PDF, or document).
Usually used in forms where users need to submit files.

## range
it creates a slider that lets users picks a number within a range
Useful for settings like volume, brightness, age etc.
<br/>

## div 
<div> is a container used to group HTML elements.
It has no visual effect by default.
Often used with CSS or JavaScript for styling or scripting.

## id 
The id gives an element a unique name
Only one element can have a certain **id.**
Used to apply specifc CSS, or for Js

## class
The class groups multiple elements under the same name.
You can use the **same class on many elements.**
Used to apply **common CSS styles**