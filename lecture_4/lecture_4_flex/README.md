# Flexbox in CSS : A guide to Flexible layouts
**Flexbox** is a CSS layout model designed to simplify the process of building 1D layouts that can dynamically adjust to different screen sizes and content sizes.

##  Basics of Flexbox
To use Flexbox, you start by applying display: flex to a container element. All direct children of that container become flex items.

    .container {
    display: flex;
    }


        <div class="container">
        <div>Item 1</div>
        <div>Item 2</div>
        <div>Item 3</div>
        </div>

## Main Properties 
For the Flex Container:
1. Flex-direction - Sets the direction of the main axis (row, row-reverse, column, column-reverse)
2. Justify-content - 	Aligns items along the main axis (flex-start, center, space-between, space-around, space-evenly)
3. align-items - Aligns items along the cross axis (stretch, flex-start, center, baseline, flex-end)
4. align-content - Aligns a multi-line flex container’s content
5. flex-wrap - Allows flex items to wrap (nowrap, wrap, wrap-reverse)


