# Day6-31r-10000coders

**List tags and formatting tags**

Three types of lists:
Ordered list: Ordered list are defined with ol tag
Unordered list: Unordered list are defined with ul tag
Descriptive list
List items are defined with li tag

**Ordered list:**
Example:
<ol>
  <li>html</li>
  <li>css</li>
</ol>

<!--Output will be:
1:Html
2.css-->
Next to define order type 

<ol type="A">
  <li>html</li>
  <li>css</li>
</ol>

<!-- By default ol(ordered list starts with number like 1. 2. 3. 
We have different attributes too not only numbers!!.

type="1"
1.Html
2.css

type="A" starts with
A.Html
B.css

type="a"
a.Html
b.css

type="I"
I.Html
II.css

type="i"
i.Html
ii.css-->

Next comes the start attribute:
<ol start="10">
  <li>html</li>
  <li>css</li>
</ol>

<!--If we use start so it starts from the that number, alphabet, or roman number-->

we also have reversed attribute:
<ol type="1" reversed>
  <li>html</li>
  <li>css</li>
</ol>

<!--
Output will be:
2.Html
1.css
-->

**Unordered list:**

<ul>
  <li>team player</li>
  <li>creative thinker</li>
  <li>good at presentation skills</li>
</ul>

<!--
Output will be:
•team player
•creative thinker
• good at presentation skills
-->

There are attributes in unordered list too!! (disc, circle, square)
<ul type="square">
  <li>team player</li>
  <li>creative thinker</li>
  <li>good at presentation skills</li>
</ul>

<!--
Output will be:
(starts with square rather than bullet points)
•team player
•creative thinker
• good at presentation skills
-->

**Descriptive list:**
Description tags are defined with dl tag
dt tag for title
dd tag for description

<dl>
  <dt>Html</dt>
  <dd>Html is known as markup language</dd>
</dl>

<!--Output will be:
Html
    Html is known as markup langauage-->

**Formatting tags**

To define visual representation of web content

First one is bold tag(b):
<p><b>Lorem ipsum</b>is known as bla bla bla</p> <!--So bold tag is used for styling and making the text bold!!-->

Next is stong tag(<strong></strong>):
<p><strong>Lorem ipsum</strong> is knowna as bla bla bla</p> <!--Here also the text btw strong tag looks like same as bold tag but here strong tag indicates importance of the text. That is why strong tag is used!!-->

**Key Differences:**
Aspect	                     <b> Tag	                    <strong> Tag
Semantic Meaning |	None, purely presentational	  |  Indicates importance or urgency
Accessibility	   |   Screen readers may ignore it	|  Screen readers may emphasize it
Default Style	   |   Bold	                        |    Bold


Next one is italic(i): also used for styling the text
<p><i></i></p>

Next one is emphasize(em): Used for importance just like strong with bold text. This is like italic but important!!

**Strong and emphasize tags comes under semantic tags!!**

u tag - used to define underline for a text
del tag- used to define strikethrough text
mark tag- used to define highlighted text

next are sub(subscript tag) and sup(superscript) tags:
sub tag is used to define subscripted text like we use for chemical names like H20
<p>H<sub>2</sub>O</p>

sup tag is used to define superscripted text like we have squares in numbers for 10^2
<p>10<sup>2</sup>+2ab<sup>2</sup></p>

next tag is abbr tag
Abbrievation tag is used to define abbrievation.
example:
<p><abbr title="Hyper Text Markup Language">HTML</abbr></p>.
In website when we hover over the HTML word, It will show the abbrievation that is Hyper Text Markup Language

Next is blockquote:
it is used to refer that text is taken from other website!!
<blockquote cite="website url here">
  arkgjfkljgslkfjdklgksjdfljgsjf gojdflkgjklsfjklgjkslg fjlkgjakljfklakljdl
</blockquote>

Next is q tag:
This is used to quote a sentence or something!!
<q>This is a quoted sentence</q>

Next is cite tag:
cite tag is used to define a title, or book name, author name like wise!!
It will make the text like italic!!

next is address tag:
It is used for contact us info..

code tag :
Code tag is used to define some block of code to represent not like regular text!!

Task: Build resume in website!!
