An SVG drawing guide
1. Intro
Assignment-5 asks you to create banner image(s), animated graphics and any SVG-related graphics or art that you wish. You are asked to use SVG code inside the body tag of your HTML files or as an imported image file (*.svg format). Using CSS or JavaScript is not allowed, since this is an HTML only assignment.

Note

If your artwork crucially depends on using CSS/JS code, please, DM the instructor on Discord with a jsfiddle example of your artwork for your request to be considered.

2. SVG basic shapes
Rectangle, circle, ellipse, line, polyline, polygon and path are the basic shapes of SVG. Each of these shapes has an element associated with it. These elements need to be inside a svg tag, as in each of these shapes would be a child of parent SVG element.

For example in the following code snippet that is a greatly simplified version of this markdown's banner graphics, you find two <rect> elements, two <circle> elements (one has a closing tag and one is an empty element!), one <polygone> element, one <text> element, a group <g> element that encloses a <path> element and a <circle> element that is traversing the path's trajectory using a nested <animateMotion> element. To view the code used to create the banner image on this document, please click here then switch to code view on the top-left corner of the viewing area.

<svg>
    <rect/>
    <circle/>
    <rect/>
    <polygon/>
    <text>
      Willkommen!
    </text>
    <g>
        <path/>
    `   <circle>
        <animateMotion/>
      </circle>
    </g>
</svg>
3. Animation
To achieve SVG animation, the following elements can be used: <animate>, <animateMotion> & <animateTransform>. The following animations created by MDN is achieved using <animateMotion>. More info is found on MDN. You are encouraged to read MDN's explanation of the other two SVG elements on its SVG Element Reference pages.



4. Examples and Tutorials
To help you getting started with SVG, the following sources are highly recommended:

W3C's SVG Primer (It has many examples with code/graphics and detailed explanation.)

SVG Tutorial artciles on MDN

Specifically the following articles are recommended for this assignment:

Getting started
Positions
Basic Shapes
Paths
Fills and Strokes
Gradients in SVG
