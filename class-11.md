#  `Images`, `Audio` & `Video` 
<hr>
 
# Images

> *CSS allows the author to manipulate images; CSS allows the manipulation of size (width and height), alignment(float and display) and presentation of an image. It also allows the addition of images as a background as well as how those images are presented (repeat, position, gradients and contract). Authors could also, create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it.*
-PRO TIP: use spirits to reduce the number of images your browser has to load.
***There are two ways that this is commonly achieved:***
- The `float` property is added to the class that was created to represent the size of the image (such as the small class in our example).
- New classes are created with names such as `align-left` or `align-right` to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.

## Repeat imgages
- The background-repeat property can have four values:
1. repeat: The background image is repeated both horizontally and vertically .
2. repeat-x: The image is repeated horizontally.
3. repeat-y: The image is repeated vertically only.
4. no-reapet: The image is only shown once.
![](https://mir-s3-cdn-cf.behance.net/project_modules/disp/35771931234507.564a1d2403b3a.gif)


## Background Position
- When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be place

## CSS3 Grading:
![](https://www.tutorialrepublic.com/lib/images/css-illustration.png)
- CSS3 is going to introduce the ability to specify a gradient for the background of a box. The gradient is created using the background-image property

## Contrast of background images
- If you want to overlay text on a background image, the image must be low contrast in order for the text to be legible.
- High Contrast
- Low Contrast
- Screen

***The following are properties used for background images:***
- `background-image`.
- `background-repeat`: repeat: The background image is repeated both horizontally and vertically 
(the default way it is shown if the backgroundrepeat property isn’t used). repeat-x: The image is
repeated horizontally only (as shown in the first example on the left). 
repeat-y: The image is repeated vertically only. no-repeat: The image is only shown once.
- `background-attachment`: specifies whether a background image should stay in one position or move as
the user scrolls up and down the page: fixed: the background image stays in the same position on the page. 
scroll: the background image moves up and down as the user scrolls up and down the page.
- `background-position`: left top, left center, left bottom, center top, center center, center bottom, right top, right center, right bottom.
- `background`: The background property acts like a shorthand for all of the other background properties.
# HTML5 video and audio
> `<video>` and `<audio>` elements allow authors to embed videos and audio into web pages. Generally this looks like this:
  
``` ruby
<video controls>
  <source src="test.mp4" type="video/mp4">
  <source src="test.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="test.mp4">link to the video</a> instead.</p>
</video>
```
> *This will allow video to play in all modern browsers. The attribute `control` enables the default playback controls. The `HTMLMediaElement` API provides features to allow you to control video and audio players programmatically; this can also be done using JavaScript. You can style the video or audio element using CSS.*
# Flash, Video and Audio
> *Flash was once a very popular technology used to add animations, video and audio. All files created in Flash are referred to as Flash movies. These are created in a Flash authoring environment by Adobe. To be able to view these additions on the website, users need to install flash plugins and flash players. Flash movies have been replaced with the introduction of video sharing sites and HTML5.*
*Example:*
``` ruby
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```
# Search Engine Optimization (SEO)
***This is basically improving you websites visibility by applying some on- an off-page techniques.***
![](https://statuslabs.com/wp-content/uploads/SEO-Pillar-Post-Art-.png)
> Search Engine Optimization (SEO): is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers. In order to determine who comes first in the search results, search engines do not only look at what appears on your site. They also consider how many sites link to you (and how relevant those links are).



## Note About This read
- About images
1. You can specify the dimensions of images using CSS ,very helpful when you use the same sized images on several pages of your site.
2. Images can be aligned both horizontally and vertically using CSS.
3. You can use a background image behind the box created by any element on a page. 



--------------------------------------------------------


[Table Of Content](https://omarxzain.github.io/reading-notes/)
