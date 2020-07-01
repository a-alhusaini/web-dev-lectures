to follow along use repl.it or install vscode with the live server extension
what is html?
html is used to show the content on the web like text/images/etc its the text in the blog post

How do i get started?
write this in a .html file

<html>
  <head>
    <title>html lecture</title>
  </head>
  <body>

  </body>
</html>
what does the above do?
the html part is a wrapper where you put your html
the head part is where hte page metadata is
what's metadata?
metadata is the data about the site that's not on the said
wait what?
if you search for something on google you'll usually find a large blue link and under that a description that stuff is metadata
all page metadata goes in the head tag
then after that we have the body tag
its where all your page goes

in the body tag write this

<h1>HELLO WORLD</h1>
what does that do?
this shows a header of size 1 on the page
what are headers
these tags h1/h2/h3/h4/h5/h6 are heading tags they are used to put larger titles/headings on your page
HELP IT DIDNT WORK!!!
make sure you put your h1 tag is inside the body tag
this works
<html>
  <head>
    <title>title</title>
  </head>
  <body>
  <h1>HELLO WORLD</h1>
  </body>
</html>

the p tag is used to write a paragraph

<p>I am a paragraph</p>

the a tag is used to make a link notice its unique syntax
the link goes inside href="LINK HERE" and the link text goes between the a tags like this
<a href="https://www.google.com">go to google</a>

i makes text italic
<i>i am italic</i>

CHALLENGE
make a link italic

SOLUTION
<a href="https://www.google.com"><i>italic link</i></a>

b makes text bold
<b>im bold</b>

strong makes text bold
<strong>im strong</strong>

WHATS THE DIFFERENCE???
the difference between these is that strong is semantic
it carries more meaning then just b

HOW DO I REMEMBER THESE
h1 = heading 1
b = bold
i = italic
a = ??? try to find something that works for you
strong = strong text
p = paragraph

ok let's say you had this inside your body tag

<i>im italic</i>
<b>im bold</b>

why are they on the same line
their on the same line because usually when you have bold text you dont want it on an entirely different line

how can i make them on different lines
you can add a line break like this

<br />

why does this one look different?
because its a self closing tag
self closing tags act like that because you dont put something inside a line break like you would with a p tag
example: <p>im text in a paragraph</p>
you dont put stuff inside line breaks and that's why they look different

you can use the button tag to make buttons
<button>CLICK ME!</button>
we will learn how to add styles to these buttons in the next lecture!

CHALLENGE MAKE A BUTTON INSIDE A LINK

SOLUTION

<a href="www.google.com"><button>go to google</button></a>

IMAGES IM HTML
to add images to html you can do this
<img src="LINKTOIMAGE" width="SOMENUMBEROFPIXELS" alt="alternative text">

see its easy i knew you guys can follow along :D

LISTS IN HTML

ol means ordered list
li means list item

make sure that you put li's inside ol's

THIS WONT WORK

<ol>
stuff here
</ol>

THIS WORKS

<ol>
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>>
</ol>

HOW DO I REMEMBER THESE?
OL = Ordered List
UL = Unordered List
LI = List Item

CHALLENGE PUT AN ORDERED LIST INSIDE AN UNORDERED LIST

SOLUTION

<ul>
  <li>
    <ol>
      <li>item 1</li>
      <li>item 2</li>
      <li>item 3</li>
    </ol>
  </li>
</ul>

notice that the inner list is a list item of the outer list
what would happen if we didnt have that?

DL means a description list
DT means Define Title
DD means Define Description

EXAMPLE

<dl>
  <dt>eggs</dt>
  <dd>a product produced by cows</dd>
  <dt>milk</dt>
  <dd>a product produced by chickens</dd>
</dl>

i did that joke again......

WHATS SEMANTIC HTML?
semantic html is a set of html tags that make sense when you write them

the best way to explain semantic html is taking an example of non semantic html

EXAMPLE
<thing>
  <thing>
  </thing>
</thing>

as you can see these tags make no sense together you dont know what does what
so below is a list of semantic html tags

header is where you ahve the introductory content of a paage
nav is where you have your navigation
main is where you put the main tag
section tag is where you put groups of content together
article tag is where you put articles
aside is used for side information
summary tag is where you put your summary
footer is where you put your footer information
copyright/email

WHAT DO I DO IF NONE OF THESE MAKE SENSE FOR WHAT IM DOING???
in that case you would use a div tag
<div>im a div</div>
the div is basically the thing tag we discussed earlier

HOMEWORK AND FINAL CHALLENGE
use all the information listed here to make a personal website it should have these features
1. Set the title tag as your name
2. Place your name in large, bold, italic text on the website
3. Put your personal information in one section of the page (i.e. your school, skills, etc.)
4. A list of your favorite activities
5. Add a picture of a person you aspire to be like/look up to
6. Provide a link to your social media
7. Add anything else that you want. Make the website unique!!!

remember the goal is to be unique its the most important point
