
## The \<form> Element
The HTML: \<form> element is used to create an HTML form for user input:

\<form>

![](https://www.html-5-tutorial.com/images/form-element.gif)


</form>
The <input> Element
The HTML <input> element is the most used form element.

An <input> element can be displayed in many ways, depending on the type attribute.

## Lists in HTML ::
- HTML offers authors several mechanisms for specifying lists of information. All lists must contain one or more list elements. Lists may contain:
- Unordered information.
- Ordered information.
- Definitions.


-for example, is an unordered list, created with the UL element:
- <UL> <LI>Unordered information. <LI>Ordered information. <LI>Definitions. </UL>

- An ordered list
**created using the OL element, should contain information where order should be emphasized

![](https://wpastra.com/wp-content/uploads/2017/11/bullet-lists-code.png)

## HTML tables
**Tables can be a useful way of organising content on a web page, particularly text.
A table is defined with the \<table> tag**

- Note
- Each row in the table is defined with the \<tr> tag.
- A table heading is defined with the \<th> tag. 
- Each cell of data in the table is defined with the \<td> tag.
  
  
  --------------------------------------------------------------------
  ## What are web forms?
  - Web forms are one of the main points of interaction between a user and a web site or application.
  
  ![](https://www.nowblitz.com/wp-content/uploads/2015/07/photodune-8110081-close-up-of-sign-up-form-xs.jpg)
  
  
  ## The \<label> Element
- The tag defines a label for many form elements. The element is useful for screen reader users.
- The element also help users who have difficulty clicking on very small regions.

## The Submit Button
   The \<input type="submit"> defines a button for submitting the form data to a form-handler.
   
   - Example: A form with a submit button:
   ```
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>
   ```

------------------------------------------------

## Events
- Events are instances or interactions with the page that trigger code, which responds to the user as a result (example: clicking, tapping, hovering, etc.). When events happen the proper term for that is “fired or been raised” and then they “trigger” a script.


### Types of events:
1. UI events: User interactions with the browser’s user interface (ex: load, resize and scroll)
2. Keyboard events: interactions with keyboards (ex: keypress, up, down)
3. Mouse events : interactions using mouse, trackpad or touchscreen (ex: click, hover, double-click )
4. Focus event: when an element gains or loses focus
5. Form event: when a user interacts with a form
6. Mutation evens: when the DOM structure is changed by script

![](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events.png)

## Event flow:
**It is important to keep track of order of which events fire. This is known as event flow; the flow can be in either direction**


# JavaScript HTML DOM EventListener

- The addEventListener() method
- Add an event listener that fires when a user clicks a button:

Events Types:
1. Mouse events 
- From Netscape 2 onwards all browsers recognize two events on links. When the user moves the mouse into the link area, the mouseover event fires. When he clicks on it the click event fires


2. Form events
- Forms recognize the submit and reset events, which — predictably — fire when the user submits or resets a form. The submit event is the key of any form validation script

3. interface events
- Interface events are events that are not caused by user actions, but by the result of user actions. When the user clicks on any element he always causes a click event. When clicking on the element has special meaning 

## Creating custom events

![](https://camo.githubusercontent.com/06e57d33847e2ec1207efb12629accda026c7567/68747470733a2f2f7468756d62732e6766796361742e636f6d2f536f757079506572696f646963416b697461696e752d73697a655f726573747269637465642e676966)

## Note:
- All events named on this page are recognized by most browsers when they occur on certain HTML elements. This means that the browser looks if any event handling script is registered to the HTML element for this event.


--------------------------------------------------------

[Table Of Content](https://omarxzain.github.io/reading-notes/)
