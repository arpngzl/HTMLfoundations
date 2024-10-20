# HTMLfoundations
<h2>Introduction to HTML and CSS</h2>
<p>HTML structures the content of a webpage, creating elements like text, links, and buttons, while CSS styles these elements by adding color, positioning, and fonts. Though often called programming languages, HTML and CSS are not, as they don’t handle logic like JavaScript, which is used to make webpages interactive. Together, HTML and CSS form the essential foundation for web development.</p>

<h2>Elements and Tags</h2>
<ul><li><h3>Elements and Tags</h3></ul>
<p>Almost all elements on an HTML page are just pieces of content wrapped in opening and closing HTML tags.</p>
<p>&lt;p&gt; is the opening tag.<br>
<button>&lt;/p&gt; is the closing tag.</p>
<p>You can think of elements as containers for content. The opening and closing tags tell the browser what content the element contains. The browser can then use that information to determine how it should interpret and format the content.

HTML has a vast list of predefined tags that you can use to create all kinds of different elements.</p>
<ul><li><h3>Void Elements</h3></li></ul>
<p>Some HTML elements do not have a closing tag. These elements just have a single tag. They are known as void elements because they are void of any content, there is nothing inside of them. No closing tag means they can’t wrap content like other tags do. for example &lt;br&gt; , &lt;img&gt; <br>
You might also see these referred to as self-closing tags.</p>

<h2>HTML Boilerplate</h2>
<ul><li><h3>Creating an HTML file</h3></ul>
<p>Create a new folder on your computer and name it html-boilerplate. Within that folder create a new file and name it index.html<br>To let the computer know we want to create an HTML file, we need to append the filename with the .html extension, as we have done when creating the index.html file.It is worth noting that we named our HTML file index. We should always name the HTML file that will contain the homepage of our website index.html. This is because web servers will by default look for an index.html page when users land on our websites – and not having one will cause big problems.</p>

<ul><li><h3>The DOCTYPE</h3></ul>
<p>Every HTML page starts with a doctype declaration. The doctype’s purpose is to tell the browser what version of HTML it should use to render the document. The latest version of HTML is HTML5, and the doctype for that version is <!DOCTYPE html>.
Open the index.html file created earlier in your text editor and add <!DOCTYPE html> to the very first line.</p>

<ul><li><h3>HTML element</h3></ul>
<p>After we declare the doctype, we need to provide an <html> element. This is what’s known as the root element of the document, meaning that every other element in the document will be a descendant of it.</p>

<ul><li><h3>Head element </h3></ul>
<p>The <head> element is where we put important meta-information about our webpages, and stuff required for our webpages to render correctly in the browser. Inside the <head>, we should not use any element that displays content on the webpage.</p>

<ul><li><h3>Body element </h3></ul>
<p>The final element needed to complete the HTML boilerplate is the <body> element. This is where all the content that will be displayed to users will go - the text, images, lists, links, and so on.

To complete the boilerplate, add a <body> element to the index.html file. The <body> element also goes within the <html> element and is always below the <head> element</p>
<ul><li><h3>Lists</h3></ul>
<ul><li><h2>Ordered list</h2></ul>
<p>Use ol to create a list where the order matters, like step-by-step instructions.
Each item is wrapped in li in conical brackets and will be numbered.</p><br>
<ul><li><h2>Unordered list</h2></ul>
<p>Use ul to create a list where the order of items doesn't matter, like a shopping list.
Each item in the list is wrapped in the li in conical brackets element, and displayed with bullet points.</p>


