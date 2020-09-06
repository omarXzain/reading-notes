
# About text Summary
--------------------
- HTML elements are used to describe the structure of the page like headings, subheadings, paragraphs
- we will learn about 2 importants parts:
1. Structural markup: the elements that you can use to describe both headings and paragraphs
2. Semantic markup: which provides extra information; such as where emphasis is placed in a sentence

## About Headings
HTML has six "levels" of headings:and we can mention he h element
- h1 to h6
- Exapmle:

<h1>h1 201 Student</h1>
<h2>h2 201 Student</h2>
<h3>h3 201 Student</h3>
<h4>h4 201 Student</h4>
<h5>h5 201 Student</h5>
<h6>h6 201 Student</h6>


## About Paragraphs
- To create a paragraph, we put and surround the words in an opening \<p> tag and closing \</p> tag
- Example:
\<p> Hello My Name is Omar \</p>
![Ptag](https://clearlydecoded.com/assets/images/posts/2017-09-04-anatomy-of-html-tag/simple-p-tag.png)

- We must know that there is alot of tag with it's defenition
1. \<b>  can make the inside text bold
- Example: \<i> Text here \</i> 
2. \<i> can make the inside text italic 
- Example \<i> Text here \</i> 

3. Superscript & Subscrip 
- \<sup> The \<sup> element is used to contain characters that should be superscript such as the suffixes of dates or

4. \<br> : used to add a line break inside the middle of a paragraph
5. \<hr> : it can add ahorizontal rule between sections using the <hr /> tag
---------------------------------------------------------------------------------

# Introducing CSS
------------------
 - We will learn how to make web pages more attractive, controlling the design of them using CSS.
 - CSS allows you to create rules that control the way that each individual box.
 
 ![Css rules](https://puzzleweb.ru/en/images/css/1_1.png)
 
- CSS works by associating rules with HTML elements and a CSS rule contains two parts: a selector and a declaration
![p rule](https://mason.gmu.edu/~amorri15/375/css-rule.jpg)

## Example About CSS
1. \<!DOCTYPE html>
2. \<html>
3. \<head>
4. \<title>Introducing CSS</title>
5. \<link href="css/style.css" type="text/css"
6. rel="stylesheet" />
7. \</head>
8. \<body>
9. \<h1>From Garden to Plate</h1>
10. \<p>A <i>potager</i> is a French term \</p>
11. \<h2>201 Ta Omar Zain \</h2>
12. \<p> iam a 201 student ... \</p>
13. \</body>
14. \</html>

## on the external css file
1. body {font-family: Arial, Verdana, sans-serif;}
2. h1, h2 {color: #blue;}
3. p { color: #red;}


-------------------------------------------------------
## Why use External Style Sheets?
- Ok 102 students lets talk about this, when building a website there are several advantages to placing your CSS rules in a separate style sheet. and ithing it's recomanded to use externa css file more than the others way because we can control the html file more and sometimes you might consider placing css rules in the same page as your HTML code 

### Example About all CSS Methods
![](https://www.bitdegree.org/learn/storage/media/images/8c4493d3-110c-4a95-8b70-7626ce2d2f4e.o.jpg)


-------------------------------------
# About Basic JavaScript Instructions
-------------------------------------
- It is about learning to read and write JavaScript, also learn how to give a web browser instructions you want it to follow. 
- It is just like a script and instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement.

### Example:
1. var today= new Date{);
2. var hourNow = today.getHours{) ;
3. var greeting;
4. if (hourNow > 18) {
5. greeting= 'Good evening';
6. }else if (hourNow > 12) {
7. greeting= 'Good afternoon';
8. }else if (hourNow > O) {
9. greeting 'Good morning';
10. } else {
11. greeting 'Welcome';}
12. document.write(greeting) ;

![](https://i.ytimg.com/vi/UZKnICO3i6U/hqdefault.jpg)


## Note: 
- **STATEMENTS ARE INSTRUCTIONS AND EACH ONE STARTS ON A NEW LINE**
- **STATEMENTS CAN BE ORGANIZED INTO CODE BLOCKS** 

### About Comments
We should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code




## USING A VARIABLE TO STORE A NUMBER

- Example:

1. var price;
2. var quantity;
3. var total;
4. price = 5;
5. quantity = 14;
6. total = price * quantity;
7. var el = document.getElementByid( ' cost ');
8. el .textContent = '$' +total; 


 ![sn](https://www.geeksread.com/wp-content/uploads/2018/03/j5SS1.jpg)


## RULES FOR NAMING VARIABLES 

1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name. 
3. You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something.
4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases. 
5. Use a name that describes the kind of information that the variable stores.
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. 

![](https://dl.dropboxusercontent.com/s/9sm26931dnyl0bs/jsvar.png)

## About ARRAYS 
**An array is a special type of variable. It doesn't just store one value; it stores a list of values** 

![](https://www.forcode.es/wp-content/uploads/2014/01/post-arrays.jpg)

- You should consider using an array whenever you are working with a list or a set of values that are related to each other


## About OPERATORS 
**They allow programmers to create a single value from one or more values**

1. STRING OPERATORS 
2. LOGICAL OPERATORS 
3. ASSIGNMENT OPERATORS 
4. COMPARISON OPERATORS 
5. ARITHMETIC OPERATORS 

- Example 
![](https://images.slideplayer.com/29/9493458/slides/slide_34.jpg)

## DECISIONS & LOOPS
**in the comparison operator, the operand on the left calculates the user's total score. The operand on the right adds together the highest scores for each round. The result is then added to the page. When you assign the result of the comparison to a variable, you do not strictly need the containing parentheses**

- Example
1[](https://cdn.javascripttutorial.net/wp-content/uploads/2016/08/JavaScript-do-while-loop.png)

-----------------------------------------------------------------------------------------------












