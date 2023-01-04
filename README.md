# Hello World

Hello, this is my first repository. I'm going to use this repository only for tutorial and such so there is nothing to see here. This tutorial contains various things related to github from git, repositories, markdown, etc. Tutorial starts with this README note that is going to explain about Markdown syntax. 

> The tutorial starts....... Now

# Markdown Basic Syntax

## Headings

To create heading, add number signs or i call it a hashtag (#) in front of a word or phrase. There are six level of Headings and it is determined by the number of hashtags. One '#' means heading level one and six '#' means heading level two. Here are the examples:

 - '\# Heading Level One'
 - '\### Heading Level Three'
 - '\###### Heading Level Six'
 
 There are a number or alternate syntax, but this one is the most recommended to use
 
 ***
 
 ## Paragraphs
 
 To create Paragraphs use a **blank line** to separate one or more lines of text. In other words, type 'spacebar' twice or if your Markdown application supports HTML you can type **'<br>' twice** to make a paragraph . If you press it only one time then it will be considered the same paragraph. For example:
 
| Markdown                 |           Output    |
| ----------------------   | ------------------  |
| This is the correct way to make paragraph. This is paragraph one<br><br>And this is paragraph two, See that there is a blank line here | This is the correct way to make paragraph. This is paragraph one<br><br>And this is paragraph two, See that there is a blank line here|
| Now, here is the wrong way to make paragraph. This is paragraph one<br>This is paragraph two. There are no blank line here so it will be considered the same paragraph | Now, here is the wrong way to make paragraph. This is paragraph one This is paragraph two. There are no blank line here so it will be considered the same paragraph |

***

## Line Breaks

To create line breaks or a new line, end a line with **two or more spaces, then type 'return' or 'enter'**. Or if your Markdown application support HTML you can type '<br>'. Here are the examples:

| Markdown                          |            Output               |
| -------------------------------   | -----------------------------   |
| There are two spaces after this line. You just cant see it.<br> this is the next line | There are two spaces after this line. You just cant see it.<br>this is the next line |
| And now an example using '\<br\>' after a line\<br\> and here is the new line | And now an example using '\<br\>' after a line<br> and here is the new line

***

## Emphasis

You can add emphasis by making text bold, italic, or both. To add emphasis, use asterisks (**\***) or underscores (**\_**) before and after a word or phrase. It is more recommended to use afterisk instead of underscores because underscores have some constraints like can't be used between words. The type of emphasis depends on the number of asterisks and underscores used.

### Bold

To bold text, use **two** asterisks or underscores before and after a word or phrase. Here are the examples:

| Markdown                                    |    Output                                  |
| -------------------------------------       |  ----------------------------------------- |
| This is \*\*bold text\*\*                   |      This is **bold text**                 |
| This is also \_\_bold text\_\_              |      This is also __bold text__            |
| Use asterisk to Bold\*\*Between\*\*Text     |  Use asterisk to Bold**Between**Text       |
| Underscore cant be Used\_\_Between\_\_Text  | Underscore cant be Used__Between__Text     |

### Italic

To italicize text, use **one** asterisk or underscore before and after a word or phrase. Here are the examples:

| Markdown                                  |    Output                                  |
| -------------------------------------     |  ----------------------------------------- |
| This is \*italic text\*                   |      This is *italic text*                 |
| This is also \_italic text\_              |      This is also _italic text_            |
| Use asterisk to Italicize\*Between\*Text  |  Use asterisk to Italicize*Between*Text    |
| Underscore cant be Used\_Between\_Text    | Underscore cant be Used_Between_Text       |

### Bold and italic

To add both bold and italic emphasis, use three asterisks or underscores before and after a word or phrase. Here are the examples:

| Markdown                                        | Output                                        |
|-----------------------------------------        | ----------------------------------------      |
| This is \*\*\*bold and italic text\*\*\*        | This is ***bold and italic text***            |
| This is also \_\_\_bold and italic text\_\_\_   | This is also ___bold and italic text___       |
| Use asterisk to Emphasis\*\*\*Between\*\*\*Words| Use asterisk to Emphasis***Between***Words    |
| Underscore cant be Used\_\_\_Between\_\_\_Words | Underscore cant be Used___Between___Words     |

***

## Blockquotes

To create a blockquote, add a '>' in front of a paragraph. Blockquotes is used to make a certain word or phrase more noticeable. Usually used by writers to "quote" certain sentences. Here are the examples

##### Markdown
```
> This is a blockquote example
```

##### Output
> This is a blockquote example

### Blockquotes with Multiple Paragraphs

Blockquotes can contain multiple paragraphs. To create this is quite straightforward that is to use a blank line after a '>'. Here are the example

##### Markdown
```
> This is the first paragraph
>
> This is the second paragraph
```

##### Output
> This is the first paragraph
>
> This is the second paragraph

### Nested Blockqoutes

Blockquotes can be nested by adding an additional '>' to the original blockquote. So the exact symbol needed is '>>'. Here's an example

##### Markdown
```
> This is a normal blockquote
>> And this is a nested blockquote
```

##### Output
> This is a normal blockquote
>> And this is a nested blockquote

***

## Lists

You can organize items into ordered and unordered list.

### Ordered Lists

To create an ordered list, add line items with numbers followed by periods. The numbers don't have to be in numerical order, but the list should start with the number one. You can also make an indented list by adding minimum 4 spaces at the start of the line. Here are the examples:

| Markdown                                            | Output                                  |
| --------------------------------------------------- | --------------------------------------- |
| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item |
|1. First item<br>1. Second item<br>8. Third item<br>9. Fourth item| 1. First item<br>2. Second item<br>3. Third item<br>4. Fourth item
|1. First item<br>2. Second item<br>&nbsp;&nbsp;&nbsp;&nbsp;1. First indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;1. Second indented item<br>3. Third item<br>&nbsp;&nbsp;&nbsp;&nbsp;1. Third indented item<br>4. Fourth item |1. First item<br>2. Second item<br>&nbsp;&nbsp;&nbsp;&nbsp;1. First indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;2. Second indented item<br>3. Third item<br>&nbsp;&nbsp;&nbsp;1. Third indented item<br>4. Fourth item|

### Unordered Lists

To create an unordered list, use dashes(\-), asterisks (\*), or plus signs (\+) in front of a line. And you can also make an indented list by adding minimun 4 spaces at the start of the line. Here's an example

##### Markdown
```
- First item
- Second item
    - First indented item
    - Second indented item
- Third item
    - Third indented item
- Fourth item
```

##### Output
- First item
- Second item
    - First indented item
    - Second indented item
- Third item
    - Third indented item
- Fourth item

### Adding Elements in Lists

To add another element in list while preserving the continuity of the list, indent the element four spaces or one tab at the beginning of the line. Here are the examples:

##### Markdown
```
- This example will be using blockquotes and paragraphs
- After this is paragraph example

    This is a paragraph, according to paragraph syntax, there has to be blank line to make a paragraph
    
- And after this is blockquotes example
    > This is a blockquote
- And this is the final item
```

##### Output
- This example will be using blockquotes and paragraphs
- After this is paragraph example
    
    This is a paragraph, according to paragraph syntax, there has to be blank line to make a paragraph
- And after this is blockquotes example
    > This is a blockquote
- And this is the final item

### Code Blocks in List
Code blocks are normally indented four spaces or one tab. When they're in a list, indent them eight spaces or two tabs.

##### Markdown
```
1. Example of a Code Blocks in a list
2. Code are below

        This is the first code line
        This is the second line
        
1. Here the continuation list
```
##### Output
1. Example of a Code Blocks in a list
2. Code are below

        This is the first code line
        This is the second line
        
1. Here the continuation list

### Images in List

Images can also be added to a list. Here are the examples

##### Markdown
```
1. There are currently no images so it will give an error

    ![Tux, the Linux mascot](/assets/images/tux.png)
    
3. The image result will give a blank image
```

##### Output
1. There are currently no images so it will give an error

    ![Tux, the Linux mascot](/assets/images/tux.png)
    
3. The image result will give a blank image

***

## Code

To denote a word or phrase as code, enclose it with bakcticks (\`). If you have multiple line of code, use three backticks before and after the code. Or alternatively, indent every line of the block by at least four spaces or one tab. If your code contains backticks (\`) use double backticks (\`\`) to denote your code.

##### Markdown
###### Word
``This `word` is a code``
###### Multiple line

``````
```
The first line
The Second line
```
``````

**OR**
```
    The first line
    The Second line
```

##### Output
###### Word
This `word` is a code

###### Multiple line
```
The first line
The Second line
```

***

## Horizontal Rules

To create a horizontal rule, use three or more asterisks (\*\*\*), dashes (\-\-\-), or underscores (\_\_\_) on a line by themselves. This horizontal rule will look like some kind of divider. Here is an example.

##### Markdown
`***`

##### Output
***
##### Output

***

## Links

To create a link, enclose the link text in brackets (e.g., \[Like this] ). And then follow it immediately with URL in parentheses. Here are the examples:

##### Markdown
`[Link to Google bruh](www.google.com)`

##### Output
[Link to Google bruh](www.google.com)

### Adding Titles
You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in quotation marks after the URL.

##### Markdown
`[Link to Google bruh](www.google.com "THIS IS SOME COOL TITLE")`

##### Output
[Link to Google bruh](www.google.com "THIS IS SOME COOL TITLE")

### URLs and Email Addresses

To quickly turn a URL or email address into a link, enclose it in angle brackets.

##### Markdown
```
<www.youtube.com>
<fakeemail@gmail.com>
```

##### Output
<www.youtube.com>
<fakeemail@gmail.com>

### Formatting Links

To emphasize links, add asterisks before and after the brackets. To denote links as code, add backticks in the brackets. Here is an example

##### Markdown
```
This is bold link **[Bold Link to Google](www.google.com)**
This is italic link *[Italic Link to Youtube](www.youtube.com)*
This is code link [`Code Link to Github`](www.github.com)
```
##### Output
This is bold link **[Bold Link to Google](www.google.com)**  
This is italic link *[Italic Link to Youtube](www.youtube.com)*  
This is code link [`Code Link to Github`](www.github.com)

### Reference-style Links

Reference-style links are a special kind of link that make URLs easier to display and read. Reference-style links are constructed in two parts: the part you keep inline with your text and the part you store somewhere else in the file so that the text is easy to read.

In reference-style link, two pair of brackets are used. The first pair of brackets is used as the name of the link. While the second pair is a label that is used to point to the actual link you're storing somewhere in your document. For the actual link, the label (in brackets), followed immediately by a colon and at least one space `[label]: www.link.com`. The URL for the link can be enclosed with angle brackets (optional) `[label]: <www.link.com>`. Then for the link title, you can use either double quotes, quotes, or parentheses `[label]: www.link.com "double brackets title"`. Here is an example

##### Markdown
```
The brackets:
[This Links to Google][label]

The actual link:
[label]: www.google.com "SOME COOL TITLE"
[label]: <www.goggle.com> 'SOME COOL TITLE'
[label]: www.google.com (SOME COOL TITLE)
```

##### Output
The brackets:  
[This Links to Google][label]

The actual link (references):  
[label]: www.google.com "SOME COOL TITLE"  
[label]: <www.goggle.com> 'SOME COOL TITLE'  
[label]: www.google.com (SOME COOL TITLE)  

***

## Images

To add an image, add an exclamation mark (!), followed by alt text in brackets, and the path or URL to the image asset in parentheses. You can optionally add a title in quotation marks after the path or URL. You can also add a link to an image by enclose the Markdown for image in brackets, and then add the link in parentheses. Here are the examples

##### Markdown
```
Normal image:
![Github Logo](https://id.wizcase.com/wp-content/uploads/2022/03/GitHub-Logo.png "This is Github Logo from the internet")

Image with link
[![Github Logo](https://id.wizcase.com/wp-content/uploads/2022/03/GitHub-Logo.png "Click here to go to Github")](www.github.com)
```

##### Output
Normal Image:  
![Github Logo](https://id.wizcase.com/wp-content/uploads/2022/03/GitHub-Logo.png "This is Github Logo from the internet")

Image with link:  
[![Github Logo](https://id.wizcase.com/wp-content/uploads/2022/03/GitHub-Logo.png "Click here to go to Github")](www.github.com)

***

## Escaping Characters

To display a literal character that would otherwise be used to format text in Markdown document, add a backlash (\) in front of the character. Here are the examples

##### Markdown
```
\- Without the backslash, this would be an unordered list. But now its just a normal dash
```

##### Output
\- Without the backslash, this would be an unordered list. But now its just a normal dash

#### Characters You Can Escape
| Character                | Name                      |
|------------------------- | ------------------------- |
| \\      | backslash        |
| \`      | backtick         |
| \*      | asterisk         |
| \_      | underscore       |
| \{}     | curly brackets   |
| \[]     | brackets         |
| \<>     | angle brackets   |
| \()     | parentheses      |
| \#      | pound sign       |
| \+      | plus sign        |
| \-      | minus sign (dash)|
| \.      | dot              |
| \!      | exclamation mark |
| \|      | pipe             |
 

### HERE'S THE EDITED PART FOR PULL REQUEST TUTORIAL

### AND THIS IS EDITED FOR PULL REQUEST TUTORIAL
 


