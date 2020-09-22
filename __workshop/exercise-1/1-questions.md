# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A screen reader is a tool used to help those who are visually impaired to navigate through a given website.
Thus complaint with Bill C-81.
https://www.codecademy.com/articles/how-to-setup-screen-reader#:~:text=A%20screen%20reader%20is%20an,various%20websites%2C%20including%20your%20own.

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img>

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
<a>, <li>

c) You want to sell designer hats. You need to receive orders from the user.
<form>, <input>,<input type="Submit"> , <label>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No, a button should take a single unique input for its own unique purpose. Otherwise the code should likely bug.

## Q5 - What is the most generic tag you can use?
<div>

## Q6 - What do the following achronyms stand for?

a) `a` anchor, for hyperlinks

b) `ol` ordered list

c) `ul` unordered list

d) `li` list

e) `tr` table rows

f) `th` table header

g) `td` table data (declare data within a cell)

## Q7 - Usually, `td` elements are children of what kind of elements?
<table> elements

## Q8 - What is the difference between td and th?
td is the data for a cell within the table, th is to name a header in the table

## Q9 - Which tag makes the text appear bigger: h1 or h3?
<h1>

## Q10 - In which situation can you use self closing tags?
When the end of said element does not need to be specified, example a link will have a beginning and end based on the length of the link itself + description, no use in specifying an end as it ends the same way everytime it is declared. Same for an image for exmaple. You desplay it, make the usual declarations and that's all you need. 

## Q11 - What is autofilling and why is it important?
autofilling helps users fill their forms faster. it will cue the browser to make an educated guess on the entries based on historical inputs used by the end-user in previous forms

## Q12 - Which attributes are always present in an img element?
image tag, the source, and the alternate description 
img, src, alt

## Q13 - Which attribute is always present for an anchor tag?
href=