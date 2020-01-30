# HTML Comprehension Questions


## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`
    the ebd of the tags are flipped
b) [false]

```html
<ul>
<li>one</li>
</ol>
```
    the colsing and opening tags are not the same
c) [true] `<ul></ul><img/><ol><li>one</li></ol>`
    the img s self closing, and the other tags are opened and closeing in proper order.

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

    a screenreader is a product that one can purchase that makes the computer use more accesible for visualy impaired individuals.
    the screenreader can identify the different "parts" (or elements) in a website and read them to the user acordingly.


    sources: https://www.afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/screen-readers
    and what scott said in class

    because of this, it is very important that we know about them, and make our work as accesible as possible. we should care beacuse we are people.


## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

    <img ... \>, <ol></ol> OR <ul></ul>, <li></li>, 

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

    <ol></ol> OR <ul></ul>, <li></li>, <a href="//link">Description</a>

c) You want to sell designer hats. You need to receive orders from the user.

    <form>, <input>, 


## Q4 - Can a button be a child of a button? Explain your reasoning

    no, it says so in the HTML reference doc. the reason wold be, I think, that the button is the clickable element. In a way, it is the "last stop" before a change. that is beacue a button has an action (submintting, linking, changing something).

    accordint to MDN: "Permitted content	Phrasing content but there must be no Interactive content"

## Q5 - What is the most generic tag you can use?

    the most generic, non spesific tag, is <div>. it is just a box for contant that we can shape in any way we want.


## Q6 - What do the following achronyms stand for?

a) `a` - anchor (for links)

b) `ol` - orderd list (bullet points)

c) `ul` - unordered list (numbers or letters or any other kind of sequencing)

d) `li` - list item (one item in a list, one entry)

e) `tr` - table row (a row of table data whithin a table)
 
f) `th` - table header

g) `td` - table data (one cell)


## Q7 - Usually, `td` elements are children of what kind of elements?

    <tr> - table row

## Q8 - What is the difference between td and th?

    <td> is one cell, in any row. <th> - is in the beginning, the header of the table. usually placed in the first row.

    the differnce is that the <th> is usually palced in the first row, and because it usually indicated the header I would assume that a screenreader (or google cralwing the web) would react to it differently

## Q9 - Which tag makes the text appear bigger: h1 or h3?

    on defualt, h1 would appear bigger then h3. but the size can be changed using CSS.

## Q10 - In which situation can you use self closing tags?

    if there are no children to the tag, if there is no content.
    for example, <img />/

## Q11 - What is autofilling and why is it important?

    autofilling is an action that a browser (or and external app) can do. This would be done on each <input> tag in a <form> tag.

## Q12 - Which attributes are always present in an img element?

    <img> tag always has a "source" attributr `src`. this is the location of the image that we want to be seen.
    An img also requires a `alt` atribue. this is the "name" or the "description" of the image that would be seen if the browser cant load the image.

## Q13 - Which attribute is always present for an anchor tag?

    `a` (anchor) tag always has an href attribute. the href is the location of the link that the a connects to.

