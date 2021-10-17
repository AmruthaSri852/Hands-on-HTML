# Hands-on-HTML
&lt;html> Journey.. &lt;/html>
## What's HTML?
### HyperText MarkUp Language
-  HyperText: Link between web pages.
-  Markup Language: Text between tags which defines structure.
-  It's a language to create web pages.
-  It defines how the web page looks and how to display content
with the help of elements.
-  It forms or defines the structure of our Web Page.
-  You need to save your file with the .html extension.
## Features of HTML:
-  Easy to learn as well as modifying.
-  For effective outcomes.
-  Can provide links or references whereever/anywhere.
-  Can display documents on platforms like Mac , Windows, Linux etc.
-  Add videos, graphics and audios making it more attractive.
-  Case insensitive language i.e. ability to ignore the difference between upper and lower case versions of a letter.
## Few Best Online Editors:
(personal opinion*)
Editors are softwares that allows you to execute HTML codes. There several amazing editors available for mac like coda or even adobe dreamweaver. These softwares are not free and not all has live preview capabilities-- Wait I even hope you check notepad, notepad++, Atom, Sublime Text also. 
Like there are really many options. I found these when I wanted to ofc. Following are few online Html Editors
1. Codepen ( I am using this one , the online html editor)
2. JSfiddle ( If you are from stackoverflow you might know this one )
3. HTML instant ( Fast but it doesn't have color-color thing, I mean the synatax highlights)
4. HTML edit ( Loads super fast, free also ads free )
5. Glitch ( This one is in its beta stage but trying is not a problem )
## HTML skeleton:
![image](https://user-images.githubusercontent.com/81810889/137637413-357d1f22-c668-4084-95d6-c3ce110a5f24.png)

### !DOCTYPE html
Instruction to the browser about the HTML version.
### html
Root element which acts as a container to hold all the code
Browser should know that this a HTML document
Permitted content: One head tag followed by one body tag
### the  head tag
Everything written here will never be displayed in the browser
It contains general information about the document
Title, definitions of css and script sheets
Metadata(information about the document)
### body
-  Everything written here will be displayed in the browser
-  Contains text, images, links which can be achieved through tags.
-  Examples: paragraph (p) tag; anchor (a) tag; image (img) tag.
## HTML Comments:
-  Comments don’t render on the browser
-  Helps to understand our code better and makes it readable.
-  Helps to debug our code
-  Three ways to comment: single line; Multiple line; Comment tag.
## HTML Elements:
-  Elements are created using tags and used to define semantics.
-  Can be nested and empty.
-  Contains things like a start tag(lets say P tag); attributes (maybe align="center"); end tag(optional); also the content in between.
### Element tags: 
### Block level
-  Takes up full block or width and adds structure in the web page
-  Always starts from new line
-  Always end before the new line
-  Examples: p tag; div tag; all h1....h6 tags; ordered and unorder list tags.

### Inline level
-  Takes up what is requires and adds meaning to the web page
-  Always starts from where the previous element ended
-  Examples : span tag; strong tag; em tag; img tag; anchor tag.
## Basic Tags: 
Enclosed within <> and 
Different tags render different meaning.
### title tag
-  Whatever is written this tag comes up in the web page’s tab
-  Defines the title of the page
-  Syntax: <title>Home </title>
### p tag
-  Defines the paragrph 
### hr tag
-  Stands for horizontal rule.
-  Dividing the web page.
### br tag
-  stands for Break tag
-  moves to next line
### img tag
-  To add images in the web page
-  Self closing tag
### h1 tag .... h6tag
-  Stands for heading tag
-  Defines heading of a page
-  h1 represents most important page in the page
-  h6 represents least important page in the page
### strong tag
-  Defines the text to be bold.
-  Replaced (b) tag cuz why not html5 goal is to make things easy.
### em tag
-  Defines the text to be bold.
-  Replaced by (i) tag for the sake of simplicity.
### ol tag
-  Stands for ordered list
-  To define series of events that take place in some order
### ul tag
-  Stands for unordered list
-  To define series of events that take place where order is not
important.
### li tag
-  Defines the list item
-  Used inside the ‘ol’ and ‘ul’ tag to define the events
### div and span tags
-  Both of these are used to group different tags .
-  Acts like a container.
-  Effective while styling.
-  Difference div is block level and span is inline level. 
### a tags
-  Used to add links in a web page
### table tag
-  Used to create a table on a web page
-  Need other tags for completing the creation of a table
- tr : for marking the table row
- th : for table header
- td : for table column data
- Everything is always enclosed within tr
- thead : to keep all header data
- tbody : to keep all body data
### form tag
-  Action attribute: It specifies the URL to send form data to
-  Method attribute: specifies the type of HTTP request(GET or
POST)
-  input: used to accept data from the user

### Some types of inputs are
-  Text: used to store text data. Syntax: type="text"
-  Password: used to enter a secure password. Syntax: type="password"
-  Placeholder: temporary text in input fields. It is generally accompanied by
"text" and "password" attributes. Syntax: placeholder="insert- text-here"
-  Button: used to include buttons in the form. Syntax: type="button"
value="insert-text-here"
-  Submit button: For creating a submit button. All the data will get submitted
when it is clicked. Syntax: type="submit"
-  Checkbox: to provide the ability to check multiple options. Syntax:
type="checkbox". To check options by default, set it with the checked attribute.
-  Radio Button: allows one to choose a single option. Syntax: type="radio". Keep
the name attribute of all the options the same.
-  select: For every possible option to select, use an option tag option
-  Text Areas: multi-line plain-text editing control. You can
specify how large the text area is by using the rows and cols attributes
-  Labels: add captions for individual items in a form. A label can
be used by placing the control element inside the label element, or by using
the "for" and "id" attributes.
-  Validations ensure that users fill out forms in the correct format, e.g.:
a. required: The Boolean attribute which makes a field mandatory:
b. email: the browser will ensure that the field contains an @ symbol.
## Attributes: 
Properties associated with each tag.
Global Attribute:
-  Title : Add extra information (hover)
-  Style: Add style information(font,background,color,size)
image tag
-  src is the attribute used in image tag to define path 
-  Width is attribute used to define width in pixels (r)
-  Alt i.e alternate text if image is not loaded
anchor tag
-  href used to define path of the link.




























