# About Links
**Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing**
1. Links are created using the <a> element
2. You can use the id attribute to target elements within a page that can be linked to
3. If you are linking to a page within your own site, it isbest to use relative links rather than qualified URLs.
4. You can use the id attribute to target elements within a page that can be linked to.
  
![](https://image.slidesharecdn.com/html-link-image-comments-141030053653-conversion-gate02/95/html-link-image-comments-12-638.jpg?cb=1414647662)

## More Info About Links
- Users can click on anything between the opening <a> tag and the closing </a> tag.

example: \<a href="site url" > Title </a>


- The text between the opening <a> tag and closing </a> tag is known as link text

- Users can click on anything that appears between the opening <a> tag and the closing </a> tag and will be taken to the page specified in the href attribut

- Every page and every image on a website has a URL (or Uniform Resource Locator). The URL is made up of the domain name followed by the path to that page or image.


![](https://weblog.west-wind.com/images/2019/Non-Navigating-Links-for-JavaScript-Handling/EmptyHref.png)


## Relative URLs
- itcan be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

![](https://www.87android.com/wp-content/uploads/2014/02/absolut-relative-url-html.png)

- If you link to the same page from two different pages you might, therefore, need to write two different relative URLs.

example;

```

To link to the homepage from the music reviews:
<a href="../index.html">Home</a>


To link to music listings from the homepage:
<a href="music/listings.html">Listings</a>


```

# Email Links
To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to. 

\<a href="mailto:jon@example.org">Email Jon</a

## Example About Links
```
<html>
<head>
 <title>Links</title>
</head>
<body>
 <h1 id="top">Film Folk</h1>
 <h2>Festival Diary</h2>
 <p>Here are some of the film festivals we
 will be attending this year.<br />Please
 <a href="mailto:omar.zein2020@example.org">
 <!-- addiaboutional content -->
 <p><a href="about.html">About Film Folk</a></p>
 <p><a href="#top">Top of page</a></p>
</body>
</html>
```


# About Layout
**Page layout is used to make the web pages look better. ... It establishes the overall appearance, relative importance, and relationships between the graphic elements to achieve a smooth flow of information and eye movement for maximum effectiveness or impact**

## More info About Layout
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

- You can include multiple CSS files in one page.

- Pages can be fixed width or liquid (stretchy) layouts.

- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.

- The float property moves content to the left or right of the page and can be used to create multi-column layouts. 

![](https://media.geeksforgeeks.org/wp-content/uploads/layout.png)

## Relative positioning

- you can move it 10 pixels lower than it would have been in normal flow or 20% to the right. You can indicate that an element should be relatively positioned using the position property with a value of relative.

-HTML
```
<body>
<h1>The Evolution of the Bicycle</h1>
<p>In 1817 Baron von Drais invented a walking
 machine that would help him get around the
 royal gardens faster...</p>
</body>
```
- CSS
```
p.example {
position: relative;
top: 10px;
left: 100px;}

```
- To move the box up or down, you can use either the top or bottom properties

![](https://css-tricks.com/wp-content/csstricks-uploads/absolute-inside-relative.png)

- To move the box horizontally, you can use either the left or right properties.

## position:absolute

o control where the fixed position box appears in relation to the browser window, the boxo ffset properties are used


@About ele The float property

allows you to take an element in normal flow and place it as far to thleft or right of the containing element as possible.


```
blockquote {
 float: right;
 width: 275px;
 font-size: 130%;
#blockquote {
 float: right;
 width: 275px;
 font-size: 130%;

}

```

## About Clearing Floats
The clear property allows you to say that no element (within) he same containing element would touch the left or righthand sides of a box. It can take the following values:


- left :
The left-hand side of the box should not touch any other elements appearing in the same containing element.


- right :
The right-hand side of the box will not touch elements appearing in the same containing element.

## About Liquid layout
- it is a designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.

- To create a fixed width layout, the width of the main boxes on a page will usually be specified in pixels 


![](https://image.slidesharecdn.com/pagelayout-150929142530-lva1-app6891/95/page-layouts-flexible-and-fixed-layout-with-css-11-638.jpg?cb=1443536908)


## Layout Grids

- Composition in any visual art (such as design, painting, or photography) is the placement or arrangement of visual elements


![](https://i.pinimg.com/originals/7d/90/0a/7d900aaac1bb49838ff31af6eabd5180.png)
 

---------------------------------------------------------------------

## WHAT IS A FUNCTION?
- Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can
reuse the function.

Example
```
<!DOCTYPE html>
<html>
<head>
Before the closing </body>
tag, you can see the link to the
JavaScript file. The JavaScript
file starts with a variable used
to hold a new message, and is
followed by a function called
updateMessage().
<ti t l e>Basic Function</title>
<l i nk rel ="stylesheet" href="css/ c03.css" />
</head>
<body>
<hl>TravelWorthy</ hl>
<div id="message">We lcome to our site! </ div>
<script src="js/ basic-function .js"></script>
</ body>
</ html> 

```

![](https://i.pinimg.com/originals/d6/39/c8/d639c8f6b83a695271a8fa79d731266f.jpg)


## HOW MEMORY & VARIABLES WORK

- Global variables use more memory. The browser has to remember them for as long as the web page using them is loaded

## WHAT IS AN OBJECT?
- Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object


----------------------------------------------------------

## 6 Reasons for Pair Programming

1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness

- While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language

-----------------------------------------


[Table of content](https://github.com/omarXzain/reading-notes)

















