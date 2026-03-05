# Day 5 - div, id, class, & script Elements, + HTML Entities
## 3.4.26
### div, id, & class Elements
#### div element
`<div></div>`  
- used as a container to group things together for styling purposes (i.e. CSS and JavaScript)
- div elements are non-semantic (unlike section elements, which are semantic)

**Note:** section elements are semantic because they communicate informaton like, "this is a section", to things like web browsers and search engines.

#### id element
id element is used to link a target in CSS. Like, if you want to make the "title" of the page red, you'd do it like this

`<h1 id="title">Movie Review Page</h1>`

and in your styles.css file, there would be  
`#title {
  color: blue;
}`

the # before "title" tells 

id element = used for specific things you want to target, no repeat names, no spaces  

#### class element
class element `<h1 class="title">Movie Review Page</h1>`, similar to id, but used to reference multiple things

#### script element
Commonly used to embed "actionable code" such as JavaScript for things like games, forms, sliders, etc.

Example:  
`<script src="path-to-javascript-file.js"></script>`  
Here the src "source" attribute is used to link an external JavaScript file

**Seperation of Concerns** = when you seperate your programs into distinct sections and have each section address a seperate concern

---------------------------------------------------------------------

### HTML Entities
#### Named Character References:  
- `&lt;` = <  
- `&gt;` = >  
*WAY EASIER TO USE `

#### Decimal Character Reference  
&#enter number value;

Example:
- `&#169;` = &#169;
- `&#174;` = &#174;

#### Hexadecimal Numeric Reference 
&#xASCII hex digits;  ASCII → American Standard Code for Information Interchange

Example:
- `&#x20AC;` = &#x20AC; (the euro symbol)
- `&#x03A9;` = &#x03A9; (omega) TOO COOL!!!!!

#### Fun Facts
- ASCII symbols: 128 total, 95 printable
- Extended ASCII: 256 total
- Unicode: over 1.1 million

