# Basic Web Techniques

## Reading Assignment 2: WWW and HTML

### Html

1. Name the components of html elements properly
   Element: The complete tag structure (e.g., <p>).
   Start Tag: The opening tag (e.g., <p>).
   End Tag: The closing tag (e.g., </p>).
   Content: The text or other HTML elements contained within the tags.
   Attributes: Additional information provided in the start tag (e.g., class, id, style).
2. Identify void elements and how they are denoted
   Void elements are HTML elements that do not have any content or closing tags. 
   They are denoted by self-closing tags or by using a closing slash before the closing angle bracket.
   Examples include <br />, <img />, <hr />, and <input />.
3. Identify attributes
   <img src="image.jpg" alt="Description">
4. Write down the correct ``DOCTYPE`` declaration for html 5
   <!DOCTYPE html>
5. Write down syntactically correct statements for the following elements
   - Article (``<article>``)
     <article>
       h1>Article Title</h1>
       <p>Article content goes here.</p>
     </article>

   - Body (``<body>``)
     <body>
       <h1>Welcome to My Website</h1>
       <p>This is the body content.</p>
     </body>

   - line break (``<br/>``)
     <br />
   - 
   - Headings (``<h1>``, ...)
     <h1>Main Heading</h1>
     <h2>Subheading</h2>
     <h3>Third Level Heading</h3>

   - Section with meta-information (``<head>``)
     <head>
       <title>Page Title</title>
       <meta charset="UTF-8">
     </head>

   - Top level element (``<html>``)
     <html lang="en">
       <head>
          <title>My HTML5 Document</title>
       </head>
      <body>
        <!-- Body content here -->
      </body>
     </html>

   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
     <img src="Team.jpg" alt="Team Image">

   - Paragraph (``<p>``)
     <p>This is a paragraph.</p>

   - Section (``<section>``)
     <section>
      <h2>Section Title</h2>
      <p>Content for the section.</p>
     </section>

   - Label appearing in the title bar (``<title>``)
     <title>Page Title</title>

   - Link to other pages (``<a>``)
     <a href="https://example.com">Visit Example.com</a>

   - Comment
     <!-- This is a comment -->

   - Head with title and meta elements
     <head>
       <title>My Page</title>
       <meta charset="UTF-8">
     </head>


## Css

1. Name the components of a css rule properly
   Selector: Target element (e.g., h1).
   Declaration Block: Enclosed in {}.
   Property: Style attribute (e.g., color).
   Value: Assigned value (e.g., red).

2. Use combinators properly: direct child, descendant, adjacent sibling, sibling
   Direct Child: div > p { ... }
   Descendant: div p { ... }
   Adjacent Sibling: h1 + p { ... }
   Sibling: h1 ~ p { ... }

3. Specify colors by color names and in hexadecimal notation
   By Name: color: blue;
   Hexadecimal: color: #0000FF;

4. Declarations for color, background color
   Color: color: red;
   Background Color: background-color: #f0f0f0;

5. Pseudo classes for the ``<a>`` element
   a:link { ... }
   a:visited { ... }
   a:hover { ... }
   a:active { ... }

6. Declaration for background image
   background-image: url('image.jpg');

7. Declaration for text alignment (left, right, center, justify)
   Left: text-align: left;
   Right: text-align: right;
   Center: text-align: center;
   Justify: text-align: justify;

8. Declaration for text decoration (overline, underline, line-through)
   Overline: text-decoration: overline;
   Underline: text-decoration: underline;
   Line-through: text-decoration: line-through;

9. Declaration for text transformation (uppercase, lowercase, capitalize)
   Uppercase: text-transform: uppercase;
   Lowercase: text-transform: lowercase;
   Capitalize: text-transform: capitalize;

10. Identify the difference between serif and sans-serif fonts
    Serif: Fonts with decorative edges (e.g., Times New Roman).
    Sans-serif: Fonts without decorative edges (e.g., Arial).

11. Declarations for font families
    font-family: 'Times New Roman', serif;
    font-family: Arial, sans-serif;

12. Declarations for font style normal and italic
    Normal: font-style: normal;
    Italic: font-style: italic;

13. Declarations for font sizes
    font-size: 16px;
    font-size: 1.5em;
    font-size: 100%;

14. Declarations for font weights
    font-weight: normal;
    font-weight: bold;
