# teched-102
This repo contains 102 course material.

```
<!DOCTYPE html>

<html>
  <head>
  </head>
    <body>
      <h1>Heading Tags</h1>

      <h2>Second Biggest Tag</h2>
      
      <h6>Smallest Tag</h6>

      <p>This is normal text.</p>

      <a href="">Link- href means hyper reference.</a>
      
      <p>All tags can have an attribute.</p>

      <img src=""/>

      <h2>List of Favourite Games</h2>
      <ul>
        <li>Elden Ring</li>
        <li>Town of Salem</li>
        <li>Runescape</li>
        <li>Rocket League</li>
      </ul>

      <table>
        <tr>
          <th>HTML TAG NAME</th>
          <th>Meaning</th>
        </tr>
        <tr>
          <td>h1</td>
          <td>Largest Heading</td>
        </tr>
        <tr>
          <td>a</td>
          <td>Link, uses href attribute</td>
        </tr>
        <tr>
          <td>img</td>
          <td>Image, uses the "src" attribute, and is self closing.</td>
        </tr>
        <tr>
          <td>p</td>
          <td>Paragraph</td>
        </tr>
      </table>
    </body>
</html>


```

## Basic HTML

### What is HTML?
**HTML** stands for *Hyper-Text Markup Language*. 

It is a language for setting the structure of a web page.

### Basic HTML Syntax

At the top of every HTML document, you should use the tag `<!DOCTYPE html>`. This tells the computer that the document type is HTML. 

Every tag can have attributes, such as `src` and `href`, which describe a feature of the tag. 

***ALL TAGS MUST HAVE AN OPENING AND A CLOSING TAG IN THE CORRECT PLACE.***

Below are some of the most important tags:

- `<html>` - this sets the space for the html.
- `<head>` - this contains the information about the HTML page, such as any links to stylesheets, and page titles to show on the browser tab.
- `<body>` - this contains all of the visible content of the HTML page.
- `<header>` - this is used for the header section of the page. The `<header>` tag is read in the same way as a `<p>` tag, which represents a separate section.
- `<h1>` - this tag is used for the main heading of a page. The heading tags go down to `<h6>`, which is the smallest.
- `<p>` - this represents a paragraph, or can also be used to represent a new section of the page.
- `<img src="image adress"/>` - the img tag can be used render an image on the page. This tag is self closing.
- `<a href="link">` - this is an anchor tag, and can be used to make a link. The attribute `href` represents Hyper Reference. 
- `<ul>`, `<ol>`, and `<li>` - these tags can be used to create lists. `<ul>` is for an unordered list with bullet points, and `<ol>` can be used to create a numbered, ordered list. The `<li>` tag is used inbetween the `<ul>` or `<ol>` opening and closing tags, and represent a list item. For example:
 
 ```
 <ul>
  <li> List Item </li>
  <li> List Item </li>
  <li> List Item </li>
 </ul>
 ```
 
 - `<table>`, `<tr>`, `<th>`, and `<td>` - These tags are used to create a table. `<table>` sets the space for the table, `<tr>` sets the rows, `<th>` sets the table headers, and `<td>` sets the table data. For example:
 
 ```
 <table>
  <tr>
    <th> Name </th>
    <th> Phone Number </th>
  </tr>
  <tr>
    <td> John Doe </td>
    <td> 01603 000 000 </td>
  </tr>
  <tr>
    <td> Jane Doe </td>
    <td> 01953 000 000 </td>
  </tr>
 </table>
 ```



