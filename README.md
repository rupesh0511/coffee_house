# coffee_house
hosted link: https://rupesh0511.github.io/coffee_house/

HTML


![Screenshot 2023-08-17 143341](https://github.com/rupesh0511/coffee_house/assets/69234169/8e442a9a-264d-4b32-aa19-5be41f8a77ef)
![Screenshot 2023-08-17 143355](https://github.com/rupesh0511/coffee_house/assets/69234169/23b589cf-b231-425b-b631-9e315d48364f)
![Screenshot 2023-08-17 143407](https://github.com/rupesh0511/coffee_house/assets/69234169/1a622d06-ff6a-435b-980b-2bd1483c274b)

Document Structure: The entire document is enclosed within the "DOCTYPE html" declaration, which specifies that this is an HTML5 document.



HTML Element: "html lang="en"" - This is the root element of the HTML document. It contains all other HTML elements and sets the language to English ("en").



Head Section: "head" - The "head" section contains metadata about the document, such as character set, viewport settings, and the document title.



Character Set: "meta charset="UTF-8"" - This sets the character encoding to UTF-8, which is a common encoding for web documents.
Viewport Settings: "meta name="viewport" content="width=device-width, initial-scale=1.0"" - This sets the viewport settings for responsive design on various devices.


Title: "title"Document"/title" - This sets the title of the document, which is displayed in the browser tab.
Linking to External CSS: "link rel="stylesheet" href="styles.css"" - This "link" element is used to link an external CSS stylesheet named "styles.css" to style the HTML content.



Body Section: "body" - The "body" section contains the visible content of the web page.



Container: "div class="container"" - This "div" element with the class "container" is used to create a container for the content.



Navbar: "div class="navbar"" - This "div" element with the class "navbar" appears to be a navigation bar or search bar.



Search Input: "input type="text" value="Search"" - This "input" element is used to create a text input field with an initial value of "Search."


Images Section: "div class="images"" - This "div" element with the class "images" likely contains a section with images.



Image Containers: "div class="image-container"" - These "div" elements with the class "image-container" appear to contain images and their descriptions.



Individual Images: "div class="image1"" - These "div" elements with the class "image1" likely contain individual images.



Image Tags: "img class="one" src="URL" alt="Description"" - These "img" elements display images and have a class for styling, a source ("src") attribute pointing to image files, and an "alt" attribute for describing the image.


Image Descriptions: "p"Cappuccino"/p" - These "p" elements provide descriptions for the images.



Description Section: "div class="description"" - This "div" element with the class "description" contains text descriptions.



Headings: "h2 class="colour""Coffee-House"/h2" - These "h2" elements with the class "colour" are used for headings with a class for styling.



Paragraphs: "p class="colour""..."/p" - These "p" elements with the class "colour" are used for paragraphs of text.



Ordered List: "ol" - This "ol" element is used to create an ordered list.



List Items: "li"Coffee-1"/li" - These "li" elements are list items within the ordered list.

CSS


![Screenshot 2023-08-17 143417](https://github.com/rupesh0511/coffee_house/assets/69234169/c35a619f-a099-43d1-94c4-95746faf19dc)
![Screenshot 2023-08-17 143429](https://github.com/rupesh0511/coffee_house/assets/69234169/e33807d7-7e98-40ab-b850-7c13c034e212)
![Screenshot 2023-08-17 143444](https://github.com/rupesh0511/coffee_house/assets/69234169/b5bf227a-8b7c-4677-9aac-e01b689ff25e)
![Screenshot 2023-08-17 143453](https://github.com/rupesh0511/coffee_house/assets/69234169/0230cea5-9d0a-4373-8c37-a32d45a54fb9)


Universal Reset:

* { padding: 0; margin: 0; box-sizing: border-box; }
This universal selector applies to all elements and resets their padding and margin to zero, while also using the "border-box" box-sizing model. It's a common technique to ensure consistent spacing and sizing in your layout.
Container Styles:



.container { width: 100%; height: 100%; background-color: #EDD4D4; }
This styles the container with a width and height of 100%, making it take up the entire viewport. It also sets the background color to a light pinkish color (#EDD4D4).


Navbar Styles:


.navbar { height: 40vh; ... }

This styles the navbar, giving it a height of 40% of the viewport height ("40vh").


.navbar > input { ... }

This styles the input element inside the navbar, making it sticky at the top, setting its width, height, background color, and more.


Image Container Styles:


.image-container { width: 100%; height: 30vh; ... }
This styles the image container, giving it a width of 100% and a height of 30% of the viewport height ("30vh").


Image Styles:


.image1 { height: 200px; width: 200px; }

This styles the individual images within the image containers, setting their height and width to 200px.


img:hover { height: 155px; width: 155px; }

This scales down the size of images to 155x155 pixels when hovering over them.


img { ... }

This styles all images, setting their margin, making them circular with border-radius, setting their width and height to 150px, adding a box shadow, and giving them a left margin.


Description Styles:


.description { ... }
This styles the description section with a width of 90%, a height of 55% of the viewport height, a rounded border, a box shadow, a background color, and padding.


List Styles:


ol { margin-bottom: 1%; color: #A52A2A; }

This styles ordered lists, adding a small bottom margin and setting the text color to brown (#A52A2A).


li { padding: 8px; }

This styles list items, adding padding around them.


Paragraph Styles:


p { margin-bottom: 2%; }
This styles paragraphs, giving them a bottom margin.
Text Color:



.colour { color: #A52A2A; }
This styles elements with the class "colour," setting their text color to brown (#A52A2A).

