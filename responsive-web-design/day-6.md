# Day 6 - HTML practice, Meta Elements & Open Graph Tags
## 3.5.26
### Basic HTML Element
`<element attribute="value">inner text</element>`

### HTML Practice
#### Bookstore Page
<a href="https://github.com/frontendfrequencies/Home/blob/a486624c46ec510e79eea634e8058b0398d4fbb5/responsive-web-design/day-6-bookstore.html" target="_blank">Raw Code</a>  
<a href="https://frontendfrequencies.dev/responsive-web-design/day-6-bookstore" target="_blank">Rendered Output</a>

#### Travel Agency Page
<a href="https://github.com/frontendfrequencies/Home/blob/a92ee8bf566ff3110d9659d6b1da4cf7e2a4934b/responsive-web-design/day-6-travel-agency.html" target="_blank">Raw Code</a>  
<a href="https://frontendfrequencies.dev/responsive-web-design/day-6-travel-agency" target="_blank">Rendered Output</a>

#### How to: Image + Hyperlink + Caption
`<figure> <a href="url" target="_blank"> <img src="image.jpeg" alt="Description"> </a> <figcaption>Caption</figcaption> </figure>`

### Meta Elements
- `<meta>`
- Void element
- Helps with SEO (Search Engine Optimization)
- `<meta name="description" content="Discover expert tips and techniques for gardening">` (write the name="description" part exactly as is)
- The text in the content attribute will appear in the web search results.

### Open Graph Tags
Tell social media platforms how to display your page when it’s shared, like the title, image, and link.

OG Property Examples:
- Title: `<meta content="Frontend Frequencies" property="og:title" />` lists the name of your content
- Type: `<meta property="og:type" content="website" />` tells social media "this is a website"
- Image: `<meta content="https://raw.githubusercontent.com/frontendfrequencies/Home/main/assets/logo.png" property="og:image" />` displays the image on social media (good to use your logo!). Recomended: 1200 by 630 pixels
- URL: `<meta property="og:url" content="https://frontendfrequencies.dev/" />` shares url with social media (like your home page) include thr FULL URL

