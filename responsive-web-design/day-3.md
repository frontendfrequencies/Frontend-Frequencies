# Day 3 - Boilerplate
## 3.1.26
### Link Element
Used to link external resourses (like stylesheets). Typically, CSS and JavaScript things live in external files and the **link elements** is what connects them with the HTML file. 

Example: `<link rel="stylesheet" href="./styles.css />`
- rel = relationship with resource and HTML
- href = location of resouce
- `./` tell computer to look in the current folder for `styles.css`

*Link Element should be placed in the `<head>`.

#### Google Fonts
Free & open source, provides you with the HTML (how neat!)

### HTML Boilerplate
Foundation for the house!

EXAMPLE:  
<img src="https://raw.githubusercontent.com/frontendfrequencies/Home/main/school-photos/boilerplate-example.png" alt="Boilerplate Example" />

`<!DOCTYPE html>` is the declaration! Also, `<!DOCTYPE html>` = HTML5

#### HTML Tag 
- Everything between `<!DOCTYPE html>` and the last `</html>`
- Includes all other elements (including head and body)
- Also lists the language. Here it is "en" for English

### Head `<head>`
- Behind the scenes data (meta data, link elements, etc.)

### Body `<body>`
- Where all the contents go. Like `<h1>`, `<h2>`, `<p>`

Drafting a boilerplate is like drafting a letter. There is a certain format. 

### UTF-8
"UCS Transformation Format"  
VERY important meta element that lives in the `<head>` section.  
UTF-8 is universal, supports every character in the Unicode character set, and includes characters and symbols from all languages.  
Include UTF-8 in every boilerplate you create - like this:

`<meta charset="UTF-8" />`  
**charset** is the "attribute" 

### Other notes
Character Encoding = A method computers use to store characters as data.   
In computing, 1 byte = 8 bits
