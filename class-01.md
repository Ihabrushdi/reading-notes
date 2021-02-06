In the browser window you can see a web page that features exactly
the same content as the Word document you met on the page 18. To
describe the structure of a web page, we add code to the words we want
to appear on the page.
You can see the **HTML** code for this page below. Don't worry about what
the code means yet. We start to look at it in more detail on the next
page. Note that the **HTML** code is in blue, and the text you see on screen
is in black.
```
<html>
<body>
 <h1>This is the Main Heading</h1>
 <p>This text might be an introduction to the rest of
 the page. And if the page is a long one it might
 be split up into several sub-headings.<p>
 <h2>This is a Sub-Heading</h2>
 <p>Many long articles have sub-headings so to help
 you follow the structure of what is being written.
 There may even be sub-sub-headings (or lower-level
 headings).</p>
 <h2>Another Sub-Heading</h2>
 <p>Here you can see another sub-heading.</p>
</body>
</html>
```
Summary
STRUCTURE
X HTML pages are text documents.
X HTML uses tags (characters that sit inside angled
brackets) to give the information they surround special
meaning.
X Tags are often referred to as elements.
X Tags usually come in pairs. The opening tag denotes
the start of a piece of content; the closing tag denotes
the end.
X Opening tags can carry attributes, which tell us more
about the content of that element.
X Attributes require a name and a value.
X To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.

# Extra Markup
Because there have been several versions of HTML, each
web page should begin with a 
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.

Comments in HTML
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:
```
<!-- comment goes here -->
```
ID Attribute

Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique)

Class Attribute

Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites.

Block Elements

Some elements will always
appear to start on a new line in
the browser window. These are
known as block level elements.
Examples of block elements are
```<h1>, <p>, <ul>, and <li>.```

``<div> ``

The `<div>` element allows you to
group a set of elements together
in one block-level box.
For example, you might create
a `<div>` element to contain all
of the elements for the header
of your site (the logo and the
navigation), or you might create
a `<div>` element to contain
comments from visitors.

Grouping Text & Elements Inline

`<span>`
The `<span>` element acts like
an inline equivalent of the `<div>`
element. It is used to either:
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements

Summary EXTRA MARKUP

X DOCTYPES tell browsers which version of HTML you
are using.

X You can add comments to your code between the
`<!-- and -->` markers.

X The id and class attributes allow you to identify
particular elements.

X The `<div>` and `<span>` elements allow you to group block-level and inline elements together.

X `<iframes>` cut windows into your web pages through
which other pages can be displayed.

X The `<meta>` tag allows you to supply all kinds ofinformation about your web page.

X Escape characters are used to include special
characters in your pages such as <, >, and 


## HTML5 Layout

HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already

Headers & Footers


The `<header>` and `<footer>`
elements can be used for:
● The main header or footer
that appears at the top or
bottom of every page on the
site.
● A header or footer for an
individual `<article>` or
`<section>` within the page.


Articles
`<article>`

he `<article>` element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.
This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.

Summary
HTML5 LAYOUT
X The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.

X The new elements provide clearer code (compared
with using multiple `<div> `elements).

X Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.

X To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google

## Process & Design
Who is the Site For?

Every website should be designed for the
target audience—not just for yourself or the
site owner. It is therefore very important to
understand who your target audience is.

Why People Visit
YOUR Website ?

Now that you know who your visitors are, you
need to consider why they are coming. While
some people will simply chance across your
website, most will visit for a specific reason.

## JAVASCRIPT
The ABC of programming
JavaScript can be used in browsers to make websites more interactive, interesting, and user-friendly. In HTML documents javascript can:

1- Access Content; for example:

Select the text inside all of the < hl > elements on a page.

Select any elements that have a class attribute with a value of note.

2- MODIFY CONTENT; for example:

Add a paragraph of text after the first < hl > element.
Change the value of class attributes to trigger new CSS rules for those elements.

3- Program rules or instructions the browser can follow

4- REACT TO EVENTS; for example:
You can specify that a script should run
when a specific event has occurred. 
For example, it could be run when:

• A button is pressed

• A link is clicked (or tapped) on

• A cursor hovers over an element

What is a script?

A script is a series of instructions that a computer can follow to achieve a goal.





