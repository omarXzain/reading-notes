
# About HTML
------------
**HTML is used to create web pages that start by writing down the words you want to appear on your page. You then add tags or elements to the words so
that the browser knows what is a heading or where a paragraph begins and ends**


# CSS
------
**CSS uses rules to enable you to control the styling and layout
of web pages. We then go on to look at the wide variety of CSS
properties you can use in your CSS rules. These properties generally fall into one of two categories**



# Structure
------------
The structure is very similar when a news story is viewed online This illustrated on the right with a copy of a newspaper alongside the corresponding article on its website.
- The use of headings and subheadings in any document often reflects a hierarchy of information
- example:
a document might start witha large heading, followed by an introduction or the most important information.
- Each topic might have a new paragraph, and each section can have a heading to describe what it covers
- Structure of Pages
The HTML code (in blue) is made up of characters that live inside angled brackets 
— these are called HTML elements. Elements are usually made up of two tags: an opening tag and a closing tag.


## About Attributes
-------------------
**Attributes provide additional information about the contents of an element**
- They appear on the opening tag of the element and are made up of two parts: a name and a value, separated by an equals sign.
- There are many important rules like:
1. The value is the information or setting for the attribute. It should be placed in double quotes
2. The attribute name indicates what kind of extra information you are supplying about the element's content. It should be written in lowercase.
3. The valueof this attribute on this page specifies it is in US English.
4. Most attribute values are either pre-defined or follow a stipulated format.
5. The value of the lang attribute is an abbreviated way of specifying which language is used inside the element that all browsers understand
- Examble :
<p lang="fr">   Paragraphe en Français <p>
 - Anything written between the <title> tags will appear in the title bar (or tabs) at the top of the browser window, highlighted in orange here. 
  

## About Extra Markup
---------------------
### we will focus and learn about:

- The different versions of HTML and how to indicate which
version you are using.
- How to add comments to your code.
- Global attributes, which are attributes that can be used on any element, including the class and id attributes.
- Elements that are used to group together parts of the page where no other element is suitable.
- How to embed a page within a page using iframes.
- How to add information about the web page using the <meta> element.
- Adding characters such as angled brackets and copyright symbols.

### DOCTYPEs
![DOCTYPEs](https://www.minddevelopmentanddesign.com/wp-content/uploads/2009/12/shutterstock_117763438.jpg)
**each web page should begin with a DOCTYPE declaration to tell a browser which version of HTML the page is using**

## Comments in HTML
<!-- -->
If you want to add a comment to your code that will not be visible in the user's browser, you can add the text between these
characters:
<!-- comment goes here -->

![](https://www.w3resource.com/w3r_images/html-comment.png)


------------------------------------------------------------
## Block Elements

![Block Elements](https://puzzleweb.ru/en/images/html/type_el.png)

**Some elements will always appear to start on a new line in the browser window. These are known as block level elements**

## Inline Elements
As I said above in the inline picture like: a b en img (in tags)
**Some elements will always appear to continue on the same line as their neighbouring elements. These are known as inline elements**## 

## IFrames
**An iframe is like a little window that has been cut into your page and in that window you can see another page
The termiframe is an abbreviation of inlineframe**
- iframe is created using the iframe> element.
There are a
few attributes that you will need
to know to use it:
src : The src attribute specifies the
URL of the page to show in the
frame.
height and width


![](https://i.ytimg.com/vi/A3yBDVwODUc/hqdefault.jpg)

-------------------------------------------------------
# HTML5 Layout
**HTML5 is introducing a new set of elements that help define the structure of a page**

- The new HTML5 layout elements and their uses.
- How they offer helpful alternatives to the <div> element.
- How to ensure older browsers recognize these elements.
 
 ## Layout Elements
**HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them**

![](https://qph.fs.quoracdn.net/main-qimg-0e07f207e1a55c01bd2b60389c08e8f9)

## Headers & Footers
- We will talk about the elements inside this this section:
- header - footer - nav and article and the aside , section , hgroup
1. About The <article> element: it acts as a container for any section of a page that could stand alone and potentially be syndicated.
2. aside element: The <aside> element has two purposes, depending on whether it is inside an <article> element or not. 

![](https://www.w3resource.com/w3r_images/html5-aside-image.png)

- When the <aside> element is used inside an <article> element, it should contain information that is related to the article but not essential to its overall meaning. 
- example:
 a pullquote or glossary might be considered as an aside to the article it relates to.

-----------------------------------------------------------------------

# Process & Design
**This section discusses a process that you can use when you are creating a new website**
Target Audience: Companies
- What is the size of the company or relevant department?
- What is the position of people in the company who visit your site?
- Will visitors be using the site for themselves or for someone else?
- How large is the budget they control?

## Why People Visit YOUR Website;
1. you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason

2. What Information Your Visitors Need: You know who is coming to your site and why they are coming, so now you need to work out what information they need in order to achieve their goals quickly and effectively.

3. Some sites benefit from being updated more frequently than others, while other content remains relatively static.

4. Site Map:
Example :
![](https://digestwebdesign.com/images/sitemap.jpg)


## WireFrames
A wireframe is a simple sketch of the key information that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.

![](https://algoworksupload.s3.amazonaws.com/new-algoworks/wp-content/uploads/2016/03/09105958/How-to-Create-the-First-Wireframe-of-Your-Application1.jpg)


### What we must learn as a 102 students?
1. It's important to understand who your target audience is, why they would come to your site, what information they want to find and when they are likely to return.
2. Site maps allow you to plan the structure of a site.
3. Wireframes allow you to organize the information that will need to go on each page.
4. Design is about communication. Visual hierarchy helps visitors understand what you are trying to tell them.
5. You can differentiate between pieces of information using size, color, and style.
6. You can use grouping and similarity to help simplify the information you present.


============================================================================

# About JAVASCRIPT
- What is a script ?
![](https://codelearnstorage.s3.amazonaws.com/Upload/Blog/tai-sao-nen-hoc-javascript-63728744439.8512.jpg)
**A script is a series of instructions that a computer can follow to achieve a goal**

## WRITING A SCRIPT
- To write a script, you need to first state your goal and list the tasks that need to be completed in order to achieve it

## WEB BROWSERS
__ARE PROGRAMS BUILT USING OBJECTS__
__THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE__
**Using the document object, you can access and change what content users see on the page and respond to how they interact with it

### HOW A BROWSER SEES A WEB PAGE
1: RECEIVE A PAGE AS HTML CODE
2. CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY 
3. USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN 

- you need to know how a browser interprets the HTML code and applies styling to it
- All major browsers use a JavaScript interpreter to translate your instructions

## HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER 

![](https://slideplayer.com/slide/17397404/101/images/2/How+HTML%2C+CSS%2C+and+JS+Fit+Together.jpg)

## LINKING TO A JAVASCRIPT FILE FROM AN HTML PAGE
**When you want to use JavaScript with a web page, you use the HTML script> element to tell the browser it is coming across a script, Its s re attribute tells people where the JavaScript file is stored**

Example:

<!DOCTYPE html>
<html>
<head>
<title>Constructive &amp; Co.</ title>
<link rel ="stylesheet" href="css/ cOl.css" />
</ head>
<body>
<hl>Constructive &amp ; Co. </ hl>
<script src="js/ add-content.js"></ script>
<p>For all orders and i nquiries please cal l
<em>SSS-3344</ em></ p>
</ body



## PLACING THE SCRIPT IN THE PAGE
You may see JavaScript in the HTML between opening <script> and closing </script> tags (but it is better to put scripts in their own files). 

==========================================================

Thx for reading :heart::heart::heart:




