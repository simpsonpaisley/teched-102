#   Class 01 Reading Notes

## Markdown and README.md Files

### What is a README.md file, and Why is it Important?

A README.md file is a markdown file, where you can write information on your project, and how to use it.

Every repository should have one.

They are important, as they let people know what your project is about, and how they can run/use it on their own computer. A README.md file can also be used to give other information about the project, such as who has contributed, and what was used in it.

### What is markdown?

Markdown is a language which can be used to format documents. It works like HTML, only it uses simpler syntax.

### Markdown Syntax

#### Headings

Headings in markdown use the amount of hash symbols relating to the size, with 1 being the largest heading, up to 6, which is the smallest.

- `#` - Heading 1
- `##` - Heading 2
- `###` - Heading 3
- `####` - Heading 4
- `#####` - Heading 5
- `######` - Heading 6

#### Code

To write code in markdown, for code over a single line, you can use backticks enclosing the code, for example:

`<html></html>`

To write a block of code, you can indent each line by 4 spaces:

    <html>
        <head>
        </head>
    </html>

Alternativly, you can use 3 backticks.

```
<html>

    <head>

    </head>

    <body>

    </body>

</html>

```

#### Unordered and Ordered Lists

To make an unordered list, you can use either the `-` key, the `*` key, or the `+`. For example:

```
    - List Item
    - List Item

```

```
    + List Item
    + List Item
```

```
    * List Item
    * List Item
```

To make an ordered list, you can simply use the numbers:

```
    1. List Item
    2. List Item
```

#### Styling

There are several styling options you can use in markdown. These are:

For **Bold** text, you can use 2 asterixes: `**bold text**`.

For *italic* text, you can use 1 asterix: `*italic text*`.

And for ***Bold and Italic*** text, you can use 3 asterixes: `***Bold and Italic Text***`

#### Inserting Images

To insert an image in markdown, you can use the syntax 

```
    ![Alt Text](image link)
```

#### Hyperlinks

To insert a link in markdown, you can use the syntax

```
    [Link Title](link address)
```


