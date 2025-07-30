# CSS Grid Layout: A Complete Guide 
CSS Grid is a powerful layout system in css that allows you to design web pages using a grid-based structure. 

## What is CSS Grid ?
CSS Grid is a 2D layout system, meaning it can control both rows and columns. 
This sets it apart from Flexbox , which is primarily 1D

### Basic Concepts
1. Grid Containter - You create a grid by setting a containter element to display:grid
2. Grid items - The direct children of the grid container automatically become grid items
<!-- <div class="container">
  <div>Item 1</div>
  <div>Item 2</div>
  <div>Item 3</div>
</div> -->

### Defining the Grid Structure
1. grid template columsn and grid template rows
  These properties define the number and size of columns and rows

.container {
  display: grid;
  grid-template-columns: 200px 1fr 2fr;
  grid-template-rows: 100px auto;
}
 1fr means one fraction of the available space.

 auto adapts to the content size.