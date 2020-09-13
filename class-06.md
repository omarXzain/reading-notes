
# About Object 
- What is the object?

1. Objects group together a set of variables and functions to create a model of a something you would recognize from the real world.
2. objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types.
3. object is an abstract data type with the addition of polymorphism and inheritance. Rather than structure programs as code and data.
4. This object represents a hotel. It has five properties and one method.
5. The object is in curly braces. It is stored in a variable called hotel. 

## More About Object
1. An object cannot have two keys with the same name.
2. The value of a property can be a string, number, Boolean, array, or another object.
3. The value of a method is always a function.

![](https://image.slidesharecdn.com/introductiontooojs-140127004826-phpapp01/95/introduction-to-object-oriented-javascript-6-638.jpg?cb=1390783865)


--------------------------------------------------------------------

# Document Object Model
**The Document Object Model specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window**


- The DOM tree is a model of web page


- This image will explain more about DOM elements

![](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)



- This is an example of body contents
```
<html>
<body>
<di v id="page">
<hl id="header">List</hl>
<h2>Buy groceries</h2>
<ul >
<li id="one" class="hot"><em>fresh</em> figs</li>
<li id="two" class="hot">pine nuts</l i>
<l i id="three" class="hot">honey</l i >
<l i id="four">balsamic vinegar</l i>
</ ul >
<script src="js/l i st.js "></scri pt>
</ div>
</ body>
</ html > 

```


## DOM
-DOM is the Document Object Model. The DOM specifies how a browser creates a model of an HTML page and the way JavaScript can access and update the page while it is in the browser. This is represented in a DOM tree which is stored in the browser’s memory.

## DOM tree
- DOM trees consist of four main types of nodes:

- The document Node (represents the entire page) Element Node (represents HTML elements)
- Attributes Node (represents attributes of elements)
- Text Nodes (represents text within elements)

## DOM Tree Figure

- Working with DOM tree
**Access the elements:**
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.
- Work with those elements:
1. Access or update text nodes
2. Work with HTML content
3. Access or update attribute values

## DOM Queries
- The methods that find elements in the DOM tree are called DOM queries. These may return one element, but they may also return a NodeList (a collection of nodes)


# TRAVERSING THE DOM

![](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.kirupa.com%2Fhtml5%2Ftraversing_the_dom.htm&psig=AOvVaw12EMO54hKgaHM58JqQn2_q&ust=1600046187032000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJiL8Nj65OsCFQAAAAAdAAAAABAJ)
- When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.

- parentNode This property finds the element node for the containing element in the HTML. (1) If you started with the first \<li> element, then its parent node would   be the one representing the \<ul> element.

  - previousSibling/nextSibling These properties find the previous or next sibling of a node if there are siblings. If you started with the first \<1i > element, it would not       have a previous sibling. However, its next sibling (2) would be the node representing the second \<li >.

- firstChild/lastChild These properties find the first or last child of the current element. 
- If you started with the <u1 > element, the first child would be the node representing the first <l i> element, and (3) the last child would be the last \<1i>.
  
--------------------------------------------------------------------

## Finding HTML Elements by CSS Selectors

- If you want to find all HTML elements that match a specified CSS selector (id, class names, types, attributes, values of attributes, etc), use the querySelectorAll() method.

- This example returns a list of all \< p > elements with class=”intro”.

```

var x = document.querySelectorAll("p.intro");
                    
```

### Changing HTML Elements
![](https://dl.dropboxusercontent.com/s/lbq1x5bw5u88hxi/changing.png)
### Adding and Deleting Elements
![](https://dl.dropboxusercontent.com/s/l3gor3jf38af19e/adding.png)

---------------------------------------------

[Teble of content](https://omarxzain.github.io/reading-notes/)
