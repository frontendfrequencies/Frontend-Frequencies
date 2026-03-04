# Day 4 - My First HTML Document!
## 3.3.26
Comment = a note written inside the code that humans can read and browsers ignore.  
Comment example = `<!-- add your notes here -->`

### Declaration
`<!DOCTYPE html>` = HTML5 = very top of page

### HTML element
`<html lang="en">` = includes language, in tis case "en" for English.

### Head Element
- `<head></head>`
- Goes at the top, before the main element.
- `<meta charset="utf-8" />` = charset attribute set to the value of utf-8. This tells the browser how to encode characters for the page. 
- Includes the title element `<title></title>` which browsers will see as the title of the page.
- Includes other meta data as well. 

### Main Element
`<main>`  
**Things that live inside the "main" (two spaces in!)**  
**Important content lives here.**  
- Adding content like `<h1>` and `<p>` here is called *Nesting*  
- Images also live inside the main. `<img src="link" alt="Description">`  
- Hyperlinks `<a href="URL">TEXT</a>`  
- `<section>Section element</section>` = used to seperate different section. Helps with SEO  
- Bullet points = "ul element" = `<ul></ul>` = unordered list of items  
- List 1-n = "ol element" - `<ol></ol>` = ordered list of items
- "li element" = `<li></li>` = used to add a list item to an ordered or unordered list
- "figure element" = `<figure></figure>` = self contained content. ALlows you to add a caption to a photo.

`</main>`

Footer element: `<footer></footer>` goes below the `<main>` element text portion. Includes liner notes (like author information)

### Other Notes
`target="_blank"` opend link in new tab (my favorite trick).

Image with a link: `<a href="URL"> <img src="image-link.jpg" alt="Description"> </a>`

figure element & ficure caption element example: `<figure> <img src="image.jpg" alt="Image description"> <figcaption>Add caption here</figcaption> </figure>`

Italicize text example: `<em>love</em>` = *love*

Bold text example: `<strong>hate</strong>` = **hate**

### My First HTML Document :)
<a href="https://github.com/frontendfrequencies/Home/blob/4002dbf24694213b3a6bff52c41c3adcff794e02/responsive-web-design/day-4-cat-photo-app-rendered-output.html" target="_blank">Code</a>  
<a href="https://frontendfrequencies.dev/responsive-web-design/day-4-cat-photo-app-rendered-output" target="_blank">Rendered Output</a>

### Using HTML for something personal - Colleen's Killer Chili <3
<a href="https://github.com/frontendfrequencies/Home/blob/33743c0403d5630e2029360371031f979fb6461b/responsive-web-design/day-4-colleens-chili-rendered-output.html" target="_blank">Code</a>  
<a href="https://frontendfrequencies.dev/responsive-web-design/day-4-colleens-chili-rendered-output" target="_blank">Rendered Output</a>
