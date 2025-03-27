## HTML scratch

Prioritize text with header elements:
	<h1>Priority 1 text</h1>
	<h2>Priority 2 text</h2>

Paragraph of text uses <p> element:
	<p>Paragraph of text</p>

To make a comment:
	<!--Insert comment here!-->

The <main> element is used to represent the main content of the body of an 
 HTML document. Helps for Engine Optimization and accessability:
  <html>
    <body>
      <main>
	<h1>CatPhotoApp</h1>
	<h2>Cat Photos</h2>
	<!-- TODO: Add link to cat photos -->
	<p>Everyone loves cute cats online!</p>
      </main>
    </body>
  </html>

NESTING is when you put the h1, h2, comment, and p elements inside the 
 main element.

A void element is an element where it uses an opening tag but
 no closing tag:
  <img>
<img> is the image element, which has no closing tag

HTML ATTRIBUTES are special words used inside the opening tag of an 
 element to control the element's behavior:
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg">
All <img> elements should have an alt attribute. The alt attribute's text is used for 
 screen readers to improve accessibility and is displayed if the image fails to load:
  <img src="cat.jpg" alt="A cat">

Link to another page with the anchor <a> element:
  <a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>
You can use the target attribute on the anchor <a> element to open links in a new tab:
  <a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>
You can turn an image or other types of content into a link:
  <a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
  </a>

The s<ection> element is used to define sections in a document, such as chapters, headers, 
 footers, or any other sections of the document:
  <section>
    <h2>Section Title</h2>
    <p>Section content...</p>
  </section>

To create an unordered list of items, you can use the <ul> element.
The <li> element is used to create a list item in an ordered or unordered list.
  <ul>
    <li>milk</li>
    <li>cheese</li>
  </ul>
The code for an ordered list (ol) is similar to an unordered list, but list items in 
 an ordered list are numbered when displayed.

The <figure> element represents self-contained content and will allow you to associate an 
 image with a caption.
A figure caption (figcaption) element is used to add a caption to describe the image contained 
 within the figure element.
  <figure>
    <img src="image.jpg" alt="A description of the image">
    <figcaption>A cute cat</figcaption>
  </figure>

To place emphasis (italicize) on a specific word or phrase, you can use the <em> element. 
The strong element is used to indicate that some text is of strong importance or urgent (bold).

The <form> element is used to get information from a user like their name, email, and other details.

The action attribute indicates where form data should be sent.
  <form action="https://freecatphotoapp.com/submit-cat-photo">
  </form>
The input element allows you several ways to collect data from a web form. Like img elements, input 
 elements are a void element and do not need closing tags.

Placeholder text is used to give people a hint about what kind of information to enter into an input.
  <input type="text" name="catphotourl" placeholder="cat photo URL">




