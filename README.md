# Day6-31r-10000coders

List tags and formatting tags

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
