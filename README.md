# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
 - 


/* General styling for the body */

body {

    font-family: 'Arial', sans-serif; /* Different font for improved readability */
    background-color: #f4f4f9; /* Light background color */
    margin: 0;
    padding: 0;
    color: #333; /* Text color */
}

/* Style for the header using an ID */

#main-header {

    background-color: #007bff; /* Blue background */
    color: white; /* White text */
    padding: 20px;
    text-align: center;
    border-bottom: 4px solid #0056b3; /* Border for aesthetics */
}

/* Style for paragraphs using a class */

.paragraph {

    font-size: 1.2em; /* Slightly larger font size */
    line-height: 1.6; /* Improve readability */
    margin: 20px;
    padding: 10px;
    border: 1px solid #ccc; /* Add subtle borders */
    border-radius: 5px; /* Rounded corners */
    background-color: #ffffff; /* White background for contrast */
}

/* Style for the image */

img {

    display: block;
    margin: 20px auto; /* Center the image */
    border: 3px solid #ddd; /* Border around the image */
    border-radius: 10px; /* Rounded corners for the image */
    max-width: 100%; /* Make image responsive */
    height: auto; /* Maintain aspect ratio */
}
index.html
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled HTML Page</title>
    <!-- Link the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header styled with an ID -->
    <header id="main-header">
        <h1>Welcome to My Webpage</h1>
    </header>

    <!-- Paragraphs styled with a class -->
    <main>
        <p class="paragraph">This is the first paragraph. It is styled using a class for better readability and aesthetics.</p>
        <p class="paragraph">Here is another paragraph with the same styling. CSS makes it easy to apply consistent styles across elements.</p>
    </main>

    <!-- Image styled directly -->
    <img src="example.jpg" alt="Example Image">
</body>
</html>
Explanation of the Code

Linking the CSS File: The <link> tag in the <head> section links the external CSS file (style.css) to the HTML file.
 
Selectors:
ID Selector: The #main-header selector is used to style the header.

Class Selector: The .paragraph selector is used to style paragraph elements.

Element Selector: The img selector is used to style the image.

Styling an Image: The img selector applies a border, rounded corners, and centering to the image.

Typography: The font-family, line-height, and font-size properties improve readability.

Margins, Padding, and Borders: These properties are applied to both paragraphs and the image to enhance spacing and aesthetics.

Happy Coding! 💻✨
