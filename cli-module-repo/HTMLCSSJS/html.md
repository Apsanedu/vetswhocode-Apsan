# HTML
## A Structure for Websites
HTML (Hypertext Markup Language) is the standard markup language used to create web pages. It provides the basic structure of sites, which is enhanced and modified by other technologies like CSS and JavaScript. The World Wide Web Consortium (W3C) is responsible for developing HTML standards. The latest version, HTML5, was finalized in 2015 and brought major improvements to media handling, graphical and multimedia elements, along with better semantic support for web documents.


# HTTP
## Hypertext Transfer Protocol
HTTP (Hypertext Transfer Protocol) is the foundation of data communication on the World Wide Web. It is a protocol that defines how messages are formatted and transmitted, and how web servers and browsers respond to various commands.

## Key Features of HTTP:
- **Stateless**: Each request from a client to the server must contain all the necessary information for the server to understand and fulfill it. The server does not retain any information about the previous requests.
- **Request/Response Model**: Communication occurs through a request-response cycle, where clients (e.g., web browsers) send requests to servers, and servers respond with the requested resources (e.g., web pages, images, etc.).
- **Methods**: HTTP defines several methods (e.g., GET, POST, PUT, DELETE) that specify the desired action to be performed on a resource.
- **Status Codes**: HTTP responses include status codes that indicate the success or failure of a request, such as 200 (OK), 404 (Not Found), and 500 (Internal Server Error).

### Tags and Elements
HTML documents are composed of `tags`, which are used to mark up the start and end of an element. Tags typically come in pairs, although some tags, known as `void elements`, are unpaired, such as `<img>` and `<br>`. An element consists of a start tag, content (if any), and an end tag.

### Attributes to tell us about Elements
Attributes provide additional information about elements. They are always specified in the start tag and usually come in name/value pairs like `name="value"`. For example, the `src` attribute of an `<img>` tag provides the path to the image you want to display.

## Basic Tags
- `<html>`: Defines the root of an HTML document.
- `<head>`: Contains meta-information about the document.
- `<title>`: Specifies a title for the document.
- `<body>`: Contains the body of the document, including content and elements.

## Basic Elements
- `<p>`: Defines a paragraph.
- `<h1>` to `<h6>`: Define headers, `<h1>` being the most important and `<h6>` the least.
- `<a>`: Defines a hyperlink.
- `<img>`: Embeds an image in the document.

### The `<hr/>` Element
The `<hr/>` tag represents a thematic break in an HTML page, and is often displayed as a horizontal rule. It is used to separate content or define a change in the content.

## Lists
- **Ordered Lists (`<ol>`)**: Contains `<li>` elements that are numbered.
- **Unordered Lists (`<ul>`)**: Contains `<li>` elements marked with bullets.
- **Description Lists (`<dl>`)**: Contains `<dt>` (term/name) and `<dd>` (description) pairs.

### Block and Inline Elements
- **Block elements** such as `<div>`, `<p>`, and `<h1>` to `<h6>`, occupy a block of space on a web page.
- **Inline elements** such as `<span>`, `<img>`, `<a>`, and `<strong>`, do not start on a new line and only take up as much width as necessary.

### Grouping Elements with `<div>` and `<span>`
- `<div>`: A block-level element used to group other elements and content in a logical section. It's often used with CSS for styling purposes.
- `<span>`: An inline element used to group small chunks of HTML elements or text within a document. It's also commonly used with CSS to style parts of the text, without causing a line break. 



# URLs
## Uniform Resource Locators
A URL (Uniform Resource Locator) is a web address that specifies the location of a resource on the internet. It consists of several components:
- **Scheme**: Specifies the protocol used to access the resource (e.g., http, https, ftp).
- **Domain**: Identifies the server hosting the resource (e.g., www.example.com).
- **Path**: Specifies the location of the resource on the server's file system (e.g., /path/to/resource).
- **Query Parameters**: Optional parameters that are appended to the URL to provide additional information to the server (e.g., ?key1=value1&key2=value2).

## Absolute and Relative URLs
- **Absolute URL**: Specifies the complete address of a resource, including the protocol and domain (e.g., https://www.example.com/path/to/resource).
- **Relative URL**: Specifies the address of a resource relative to the current page's location. It does not include the protocol or domain (e.g., /path/to/resource).

# Creating Links with `<a>` Element
The `<a>` element, also known as the anchor element, is used to create hyperlinks in HTML. It has an `href` attribute that specifies the URL of the linked resource.
```html
<a href="https://www.example.com">Visit Example</a>
```

# Images, Audio, and Video Tags
HTML provides tags to embed various media types in web pages:
- **Images (`<img>`)**: Used to embed images in web pages.
  ```html
  <img src="image.jpg" alt="Description of Image">
  ```
- **Audio (`<audio>`)**: Used to embed audio files in web pages.
  ```html
  <audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  ```
- **Video (`<video>`)**: Used to embed video files in web pages.
  ```html
  <video controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video element.
  </video>
  ```

# Tables
Tables are used to display data in rows and columns.
```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```
- `<table>`: Defines a table.
- `<tr>`: Defines a row in the table.
- `<th>`: Defines a header cell in the table.
- `<td>`: Defines a data cell in the table.


# HTML Forms
HTML forms are essential for collecting user input on websites. They contain form elements such as text fields, checkboxes, radio buttons, and buttons, which allow users to interact and submit data to web servers.

## Key Components of HTML Forms:
- **`<form>` Element**: The container for all the form elements. It can specify the action (server page that will receive the data) and method (GET or POST).
  ```html
  <form action="submit.php" method="POST">
    <!-- form elements go here -->
  </form>
  ```
- **Input Elements (`<input>`)**: Used to create various types of input fields, like text, password, radio buttons, checkboxes, etc.
  ```html
  <input type="text" name="username">
  ```
- **Label (`<label>`)**: Provides a user-friendly name for form controls and improves accessibility.
  ```html
  <label for="username">Username:</label>
  <input type="text" id="username" name="username">
  ```
- **Submit Button (`<input type="submit">`)**: Used to submit the form to the server.
  ```html
  <input type="submit" value="Submit">
  ```

# HTML Frames (Deprecated)
HTML frames were used to divide the browser window into separate sections, each displaying a different HTML document. They are largely deprecated due to usability and accessibility issues and have been replaced by CSS for layout purposes.

## Structure of Frames:
- **`<frameset>`**: Replaces the `<body>` tag and defines how to divide the page into frames.
  ```html
  <frameset cols="50%,50%">
    <frame src="left.html">
    <frame src="right.html">
  </frameset>
  ```
- **`<frame>`**: Specifies the content of each frame.

## Alternative to Frames:
- **CSS Grids and Flexbox**: Modern CSS features that provide more flexibility and control over layouts without the drawbacks of frames.

# CSS
CSS (Cascading Style Sheets) is used to style and layout web pages. It allows developers to separate content from design and control how HTML elements look and feel.

## Relationship with HTML:
CSS enhances HTML by providing a powerful and flexible way to visually enhance web pages. Its use with HTML is indispensable for creating professional, visually appealing web content.
- **Separation of Content and Style**: HTML provides the structure, while CSS defines the appearance.
- **Selectors**: CSS uses selectors to target HTML elements and apply styles to them.
  ```css
  p {
    color: red;
  }
  ```
- **External, Internal, and Inline Styles**: CSS can be included in HTML documents in three ways:
  - **External CSS**: Styles are placed in a separate file.
    ```html
    <link rel="stylesheet" href="styles.css">
    ```
  - **Internal CSS**: Styles are defined within a `<style>` tag in the `<head>` section.
    ```html
    <style>
      body { background-color: blue; }
    </style>
    ```
  - **Inline CSS**: Styles are applied directly to elements using the `style` attribute.
    ```html
    <p style="color: green;">This is green text.</p>
    ```

