# What is Markdown?
####### Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.
######## You can use Markdown most places around GitHub:
•	Gists
•	Comments in Issues and Pull Requests
•	Files with the .md or .markdown extension
Example: making some words **bold** or *italic* 
######## Markdown, Syntax guide usage: 
1.	Typing headers #h1, ##h2
2.	 Emphasis by changing font type  *italic*   **bold**
3.	Making ordered and unordered list
*. Item 1
*. Item 2
*. Item 3
*. Item 3a
*. Item 3b
4. Embedding images  ![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
5.  embedding links 
6. embedding tables 
7. embedding emojies 
8.  syntax highliting


Nested Lists
You can create a nested list by indenting one or more list items below another item.
To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom, you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.
1. First list item
   - First nested list item
     - Second nested list item
 
 
To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.
In this example, you could add a nested list item under the list item 100. First list item by indenting the nested list item a minimum of five spaces, since there are five characters (100. ) before First list item.
100. First list item
     - First nested list item
 
You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven spaces (␣␣␣␣␣-␣) before the nested list content First nested list item, you would need to indent the second nested list item by seven spaces.
