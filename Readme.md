# 1. Getting started 

* WYSIWYG(what you see is what you get) - software that allows content to be edited in a form that
* markdown - applying styling to text as its written

## Additional Resources
* John Gruber's Markdown documentation
* Markdown tutorial
* Awesome Markdown
* Typesetting Markdown

## **this text is bold and is heading 2**

# 2. Doing things with Markdown

* Jekyll - popular static site generator. Good for people with HTML, CSS and version control knowledge. 

# Basic syntax

---
## Heading
1-6 levels of heading using `#`

### **Alternate Syntax**
Heading 1
=
shortcut `=` for heading 1

Heading 2
-
shortcut `-` for heading 2

---
## Paragraphs
I really like using Markdown.

I think I'll use it from now on.

---
## Line Breaks
I don't know how this works.  
Ok I got it.
Just add 2 spaces at the end of the line you want to end and start a new one

---
# Emphasis

## Bold
bolding is done with 2 of `*` or `_`  
I love **bold** moves  
I love __bold__ moves  
Love**is**bold

## Italic
Italic uses only 1  
The *cat's meow*  
The _cat's meow_  
A*cat*meow.

## Bold and Italic
You can use both at the same time if you place 3  
Example: `_**something**_`. They don't have to be matching  
***Important*** Text  
__*Important*__ text

---
## Blockquotes
They use `>`

This is the first paragraph
> and this is the second 
> 
>> awas  
> sfes
> 
> wasd

You can have multiple paragraphs and can **nest** them

---
## Lists
        ### 1. Ordered List
        3. wasdwa
        4. wasdw
        3. wasd
        ### 2. Unordered List
        - First item
        + Second item
        * Third item

### 1. Ordered List
3. first item
   4. first item in first item
3. second item
### 2. Unordered List
- First item
+ Second item
* Third item

---
## Code Blocks and code
* Code blocks are indented 4 spaces or a tab.  
* When in a list **indent** double that

1. Example of code block inside a list
2. Example item number 2
3. Look at the following `code`

             Print("Hello world")
4. something else
        
---
## Images and Links

Here `[Pikachu]` is used as alternative if the image isn't available
The only syntax for images is `![alt](image.png)` and for link just don't place the `!`.  
A **[Pikachu](https://www.pokemon.com/us/pokedex/pikachu)**  
<https://www.pokemon.com/us/pokedex/pikachu> enclose a link in angle brackets to make it into a link
![Pikachu](pika.png)    
emphasazing works the same with links

---
## Horizontal Rules `---`

Better separation of different parts of the document.
Will use a lot

---
# Extended syntax

## Tables

using `:` to align content

|  Table Head |     something else      |
|------------:|:-----------------------:|
|  Table body | something else entirily |
|        ---- |       asdwassadwa       |

for easier table creation [Table Generator](https://www.tablesgenerator.com/markdown_tables)

## Fenced code blocks

You can use a language key word to highlight the syntax `python, json` etc.
```python
print("Hello world")
```

# Partially or Not Supported syntax

## Footnotes (Partially supported)

Here's a simple footnote,[^1]. And here's a longer one.[^bignote]

[^1]: Thisdwasd


[^bignote]: wasdwa

    wasdwa


## Heading IDs (Not Supported)

### My Great Heading {#custom-id}

