# jerr-chen.github.io
My Webpage =)

I am creating a webpage for myself that explains my interests in my career and outside of my career. This is a webpage that will supplement my resume, and help recruiters understand who I am as a person.

In addition to creating a bio about myself and past experiences, I am using this project as my method for learning about web development starting off with HTML, CSS, and JavaScript.

### <b>The Journey</b>
The resources that I will be using to help me on the journey will be cited below if you are interest in creating your own webpage. I will also include what topics I looked for when learning these new languages.

##### DAY 1
<p>I started off looking at a sample code to understand what I will be expecting. The very first thing I saw was <!DOCTYPE html>. DOCTYPE isn't in any of the languages that I know, so this is the first thing I Googled, and I came across the link(1). There were also various tags that are used, and the explanation in the link(1) referred to them as elements. I Googled 'html elements', and I found the link(2), which turns out to be a tutorial with various resources.</p>
<p>From what I understood, the only thing html can do by itself is organize text with various fonts. In order for me to use colors extensively and design the webpage, I would need to use CSS. According to link(3) there's three different ways I can use CSS with HTML: inline, internal, and external.</p>
<p>Now I bring in JavaScript. I've heard about JavaScript a lot, but I never quite understood how it was used with web development. In link(4), my take away is that JavaScript is create the behavior or the webpage on the client side. To use JavaScript with the program, I just use the 'script' tag.</p>

##### DAY 2
<p>Trying to understand the purpose of the title tag. According to the image in the link(5). Every tab in a browser has a title. Before I applied the title tag, my tab only had my web address on it. After applying a title, it says 'Jerry Chen: The Journey'.</p>
<p>Learning how to add photos using link(6). It appears that common practice is creating a subdirectory called 'images' and adding all the photos into that directory. Then I use HTML to pull the photo from the folder and add attributes to it.</p>

##### Day 3

Most of my learning today will be through link(7). I thought it would be easier to learn HTML & CSS through an organized lesson by codeacademy. I learned the title should always be in the the head element, so I corrected my code and moved the title element.

I then learned about two types of lists unordered and ordered lists. Unordered are bullet point lists and ordered lists have numerical associations. The "ul" and "ol" elements can't interpret raw text, but it can organized "li" elements together.

In order to add hyperlinks connecting my webpage to the rest of the internet, I need to use "a" (aka anchor element). In addition to using the "a" element, I need to add an attribute href, which lives in the openning tag. There's two parts of an attribute: name of attribute and value of attribute. The name in this case is href, and the value is the web address string. Cool stuff. The anchor element also has a target attribute, which opens the link in a new window (new tabs in modern browsers). The value for target is "_blank". The cool thing about the an anchor element is that you can wrap any other element with "a" and it becomes a link of some form.

The img element are self closing elements. Meaning it only has an openning tag that ends with />. I have used the src, alt, and style attributes. The src is like href but for an image, which could be an address to the image or an image in a local directory. alt is the the text that shows if the image doesn't load properly. style is how the image should be displayed.

CSS is used to modify the text of HTML to become visually appealing. According to Code Academy, it can be used to modify colors, font types, font sizes, shadows, images, element positioning, and more. The inline CSS, as I learned about in a previous day, must be placed in the head element. The general syntax of CSS is an element selector followed by curly brackets and it's contents. For example, all elements that are selected will have these values. * is the universal selector
	
	; selector {
	; 	property: value;
	; }

It's generally good practice to separate HTML and CSS code into two separate folders even though CSS can be incorporated into the head element of HTML. The "link" element is used to associated the two files together. Similar to a #include in C and C++ but different. It must be included in the head element that requires the following attributes: href, type, rel. href is the path to the CSS file. type is the type of document, which is text/css in this case. rel is the relationship between the two, in this case it's a "stylesheet".

##### Day 4

Learning about colors for CSS. There's 3 different ways to specify the color values: using named colors (147 colors: link(8)), using rgb values (each ranging from 0-256: link(9)), or hex values, which are the same as rgb values but different representation. to represent rgb use rgb(red, green, blue).

Aside from these three representations, there's also HSL (Hue, Saturation, and Lightness). Hue is the color wheel from 0 to 360. Saturation is the amount of gray in a color from 0% to 100% where it represents the shade of gray and 100% is full saturation. Lightness is the amount of white in a color. Like saturation, it ranges from 0% to 100%, but 0% is black, 100% is white, and %50 is normal. To represent hsl we use hsl(hue, saturation, lightness).




### Links
1. https://www.w3schools.com/tags/tag_doctype.asp
2. https://www.w3schools.com/html/html_paragraphs.asp
3. https://www.w3schools.com/html/html_css.asp
4. http://study.com/academy/lesson/what-is-javascript-function-uses-quiz.html
5. https://moz.com/learn/seo/title-tag
6. https://www.w3schools.com/html/html_images.asp
7. https://www.codecademy.com/learn/learn-html-css
8. http://www.colors.commutercreative.com/grid/
9. https://color.adobe.com/create/color-wheel/







