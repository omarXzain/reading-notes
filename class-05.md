
# Summary About Images, Color, Text
-----------------------------------

## Images
1. The <img> element is used to add images to a web page.
2. You must specify a src attribute to indicate the source of an image.
3. You must specify alt attribute to describe the content of an image.
4. Photographs are best saved as JPEGs, PNG , Gif
5. Must consider the image size to fit the website and make it lighter to laod

## How to add images to pages

**There are many reasons why you might want to add an image to a web page: youn might want to include a logo, photograph, etc**

- We must cosider 4 things:
1. Include an image in your web pages using HTML
2. Pick which image format to use
3. Show an image at the right size
4. Optimize an image for use on the web to make pages load faster

![](https://thumbs.gfycat.com/EnchantingInbornDogwoodtwigborer-small.gif)

## Adding Images

- \<img> element is used To add an image into the page, This is an empty element (which means there is no closing tag).

- src : this tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site

- title : You can also use the title attribute with the <img> element to provide additional information about the image

- alt : This provides a text description of the image which describes the image if you cannot see it

- Example Code 

```

<img src="images/quokka.jpg" alt="A family of
 quokka" title="The quokka is an Australian
 marsupial that is similar in size to the
 domestic cat." />
 
```

![](https://www.nerdpress.net/wp-content/uploads/2012/01/image-tag.gif)

## Height & Width of Images
- height: This specifies the height of the image in pixels.
- width : This specifies the width of the image in pixels.

```

<img src="images/quokka.jpg" alt="A family of
 quokka" width="600" height="450" />

```

![](https://www.wikihow.com/images/thumb/0/00/Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg.webp)


## Aligning Images 

- There are three values that the align attribute can take that control how the image should align:

1. top : This aligns the first line of the surrounding text with the top of the image.

2. middle This aligns the first line of the surrounding text with the middle of the image.

3. bottom : This aligns the first line of the surrounding text with the bottom of the image.



## Rules To Create An Image

- There are 3 rules to creating images for your website:

1. Save images in the right format

2. Save images at the right size

3. Use the correct resolution


## Animated GIFs
- Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations
- Example
![](https://cloudinary-res.cloudinary.com/image/upload/c_fill,w_770/dpr_3.0,f_auto,fl_lossy,q_auto/Animations_with_HTML5_2000x1100_v2.gif)



## Transparency

- Creating an image that is partially transparent for the web involves
- selecting one of two formats:
1. png

![](https://lh3.googleusercontent.com/proxy/kS5XXbxQtIr4dPVcCFu0eKEmeg4eRkhlII0S9MKhKMOqBTigjjlScMbl6Air_668o2l_V5Ekr4B5lKZ0tbkPQFgrkZ_MbmumJ3KGpuVFlQ0R6dkjHLc)

2. Transparent GIF

![](https://thumbs.gfycat.com/LameDifferentBalloonfish-small.gif)


-----------------------------------------------------------


# Color
- Color can really bring your pages to life.

- You can specify any color in CSS in one of three ways:

### rgb values
- it express colors in terms of how much red, green and blue are used to make it up.
- example: rgb(100,100,90)

### hex codes

- These are six-digit codes that represent the amount of red, green and blue in a color

### color names

There are 147 predefined color names that are recognized by browsers. For example: Blue 


## Tip From me in Colors
1. Color pickers can help you find the color you want.

2. Color helps to make the design looks better and attractive 

3- It is important to ensure that there is enough **contrast** between any text and the background color


--------------------------------------------------------------


# Texts 

**There are properties to control the choice of font, size, weight, style, and spacing**

1. You can control the space between lines of text , and words. 
2. Text can also be aligned to the left, right, center, or justified
3. You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text


## How To Decorate Text
1. font-family: The font-family property allows you to specify the typeface that should be used for any text inside the element(s) to which a CSS rule applies.

- Example

```
body {
font-family: Arial, Verdana, sans-serif;
font-size: 12px;}
h1 {
font-size: 200%;}
h2 {
font-size: 1.3em;}
```

![](https://docs.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/platform-apis/images/ff975652.font-family(en-us,vs.85).png)


- it shows differnt ways and styles and make the font more attractive to read



### Type Scales
- The default size of text in a browser is 16 pixels
example: 
![](https://images.squarespace-cdn.com/content/v1/54becebee4b05d09416fe7e4/1425914394941-S127VB3HRPLSPZ562XWQ/ke17ZwdGBToddI8pDm48kO-nusLtcAdtf47f8bIHOgBZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PI72_1OLaTunhchyuOdTf8T3vik7E7BMF3ItyeR7Dq9fQ/image-asset.png)

## More About Fonts

1. font-weight
- normal : This causes text to appear at a normal weight.
- bold : This causes text to appear bold.


2. font-style
- normal : This causes text to appear in a normal style
- italic : This causes text to appear italic.
- oblique : This causes text to appear oblique

```
.omar {
font-style: italic;}

```


## text-decoration
- none : This removes any decoration already applied to the text.
- underline : This adds a line underneath the text.
- overline : This adds a line over the top of the text.
- line-through : This adds a line through words.
- blink : This animates the text to make it flash on and off

```
#omar {
text-decoration: underline;}
a {
text-decoration: none;}

```

- We Will use this code to color the h2

```
#CSS
h2{
  animation: blinker 1s linear infinite;
  color: rgb(214, 34, 190);
}

@keyframes blinker {
  50% {
    opacity: 0;
  }
}

```

![](https://dl.dropboxusercontent.com/s/4vt107jluso9aky/blinkx.gif)


## text-indent
The text-indent property allows you to indent the first line of text within an element. 


```
h1 {
background-image: url("images/logo.gif");
background-repeat: no-repeat;
text-indent: -9999px;}
.credits {
text-indent: 20px;}

```
## Styling Links

1. :link : This allows you to set styles for links that have not yet been visited
2. :visited : This allows you to set styles for links that have been clicked on. 

```

a:link {
color: deeppink;
text-decoration: none;}
a:visited {
color: black;}
a:hover {
color: deeppink;
text-decoration: underline;}
a:active {
color: darkcyan;}

```

## Responding to Users

hover : This is applied when a user hovers over an element with a pointing device such as a mouse. 

active : This is applied when an element is being activated by a user

focus : This is applied when an element has focus

![](https://i.pinimg.com/originals/e7/1d/9f/e71d9fa2e822556d63d6bf5075f174a3.gif)

------------------------------------------------------------------


[Table Of Content](https://omarxzain.github.io/reading-notes/)
