Makes all layouts predictable and prevents overflow issues
Applies to all elements  Make layouts predictable
margin:auto tells the browser to automatically calculate the left and right margins-usually to center an element horizontally
nav .menu{
    max-width:1250px;
    background: red;
    margin:auto;
}
meny will get horizontally centerd in this nav container

✅ display: flex affects only the direct children of the element it's applied to.

align-items:center; Center the items along the cross axis that is y-axis.

display:inline-flex; An inline elements like span  doesn't break to a new line 

so display:inline-flex; tries the elements to adjust in one line without wrapping to another line


    background-position: center;
    background-size:cover;

    ✅ What it does:
Makes sure no empty space is left.

Maintains the aspect ratio of the image.

Will zoom in the image if needed to fill the full width and height of .img.




transform: translate(-50%, -50%);
This moves the element by:
-50% of its own width to the left
-50% of its own height upward