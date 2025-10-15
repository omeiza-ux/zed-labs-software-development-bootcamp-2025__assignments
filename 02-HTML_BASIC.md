# HTML BASICS
HTML (HyperText Markup Language) is the standard language used to create web pages.
It structures the content of a webpage using tags (like **p**, **h1**, **img**, etc.).

## STRUCTURE OF HTML
1. **!DOCTYPE html** → tells the browser it’s HTML5.

2. **html** → root element of the page.

3. **head** → contains meta info (title, links, etc.).

4. **title** → name that shows in the browser tab.

5. **body** → main content (text, images, links, etc.). .


## HTML CODE
```html 
<!DOCTYPE html>
<html>
    <head>
        <title>My First Web Page</title>
        <h1>wellcome to computer science federal polytechnic bida</h1>
        <h2>The school that made the lion bark</h2>
        <h3>smaller</h3>
        <h4>smaller</h4>
        <h6>smallest</h6>
        <p>thanks for coming</p>
        <style>
            p{
                font-weight: bold;
            }
        </style>
    </head>
    <body>
<img src="images/IMG-20250308-WA0073.jg" alt="NO IMAGE">

   </body>
</html>
```

## COMMON HTML TAGS
1. Headings: html has up to six heading types with each having distinct size.

```html
  <h1>Main Heading</h1>
  <h2>Sub Heading</h2>
```

2. Paragraph: the <P> tag defines a paragraph.

<p>This is a paragraph of text.</p>


3. Links: <a> defines a link, 'href' defines the location of the link, and 'visit Google' represents or contain the link in the browser.
```html
<a href="https://google.com">Visit Google</a>
```

4. Images: images are called using the <img> tag, 'src' is the source of the image, and 'width=200' represent the size of the image in pixel
```html
<img src="image.jpg" alt="Description" width="200">
```
5. Tables:
```html
<table border ="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Victor</td>
    <td>20</td>
  </tr>
</table>
```
- An HTML table is made up of:
**table** → defines the table.
**tr** → defines a row.
**th** → defines a header cell (bold & centered by default).
**td** → defines a data cell (normal text).