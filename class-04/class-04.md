# Class 04 Reading Notes  

## Wireframes and Website Structuring

## The Website Design Process

There are several steps to complete before coding a website. These are as follows:

1. **Wireframe** - this is just a rough sketch of the layout of a website. 
2. **Mockup** - this is the layout of the website made to scale. 
3. **Prototype** - this is the final stage, and will have the dimensions, fonts, colours, and other stylings, to show what the completed website will look like. 

![Wireframe, Mockup, and Prototype](https://media.licdn.com/dms/image/C4E12AQEPGiDGz9YU1A/article-cover_image-shrink_600_2000/0/1605200070733?e=1680739200&v=beta&t=at78JsPU7HI4izme3q90jf7SIKxUJr1tpy2JMRAEtBI)
[Image Source](https://www.linkedin.com/pulse/what-difference-between-wireframe-mockup-prototype-riana-butler)


### Basic HTML 


#### What is HTML?
**HTML** stands for *Hyper-Text Markup Language*. 

It is a language for setting the structure of a web page.

#### Basic HTML Syntax

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



