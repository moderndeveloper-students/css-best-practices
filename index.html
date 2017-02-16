<div class="aboutCourse aboutChapter">

<h2>About this Chapter</h2>

Ensuring that their CSS is clean often becomes a secondary concern for developers. As easy as it may seem to write CSS, the rules can flow in from multiple files<!--COMMENT; ROBIN: What does this mean? What do the two parts of this sentence have to do with one another? What rules? (I assume CSS rules, but that is not clear) "rules can flow in from multiple files" Can flow? What controls this flow? Flow? Like a stream of water? flowing from multiple files to where? Why does any of this matter?-->. CSS has no mechanism for compile-time or run-time error checking; so, when CSS eventually does not work, the browser doesn't draw things right, but no error messages are generated.

We have all written large amounts of CSS code throughout this course, but this chapter will specifically stress some of the preferred practices for writing clean, well-formed, and accessible CSS code. They range from marking up the CSS to using certain naming conventions in order to organize our CSS code better.
<span class="exampleBefore">Prerequisites:</span>
<ul>
<li><em>Course</em>: Mastering JavaScript and Modern Web Development</li>
<li>Mastering HTML</li>
<li>Mastering CSS</li>
</ul>

<span class="exampleBefore">Approximate Time to Complete:</span>
<span class="exampleAfter">Assignment Due Date:</span>
<span class="exampleBefore author">Author:</span> <span class="highlightAuthor">Anil Verlekar</span>
</div>

<h2>General Practices</h2>

CSS code can easily spiral into a maintenance nightmare if certain best practices are not followed. Badly written and uncommented CSS code creates confusion; especially when another developer attempts to work with the code. By badly written code, we mean code that has style rules repeated all over the stylesheet, code with poorly named classes, or code that is not split into separate modules. Writing clean and modular CSS code is a good habit and is essential for ease of maintenance and housekeeping.

It sometimes happens that a developer must update an existing property but has a hard time finding the corresponding rule set. This happens when the CSS code is poorly commented or when the CSS rules are not named according to the task they perform.

Imagine a situation where we are asked to update the font color of all <code>section</code> elements from black to gray, but the concerned CSS selector is named, for instance, <code>.content</code>. Such a name is not intuitive based on the task it should perform (formatting the <code>section</code> element) and narrowing our search down to this particular selector becomes nearly impossible if the code is not commented.

This section will discuss a few techniques, tips, suggestions, and commonly adopted practices that will help us write clean, manageable, and beautiful stylesheets. We will group these best practices based on the following broad categories: <em>General Practices</em>, <em>Organization</em>, <em>IDs, Classes, and Selectors</em>, <em>Properties</em>, <em>Shorthand Notation</em>, and <em>Miscellaneous Tips</em>.<!--COMMENT; ROBIN: The sections don't actually follow these categories. It really seems like they should-->

<h2>Syntax and Commenting</h2>

Following the correct syntax and conventions is the first step in keeping CSS code well organized and easy to comprehend. Let's discuss some of the rules we can apply in our day-to-day encounters with CSS code.

<h3>Remember the Semicolon</h3>

Many rookie developers and designers make the mistake of leaving off the semicolon at the end of every CSS rule declaration. Since many programming languages use the semicolon to terminate a line of code, experienced developers have a natural tendency to add it, but many new developers forget it, especially for CSS rules:

<pre lang="javascript" line="1">
/* BAD */
p {
    color: #C0C0C0;
    font-family: 'Verdana'
}

/* GOOD */
p {
    color: #C0C0C0;
    font-family: 'Verdana';
}
</pre>

A semicolon is technically not required for the last of multiple rules, but adding it is a good practice. Leaving it off does not create an issue if the declaration has just a single rule, but if it has multiple rules, a semicolon is required at the end of every rule. As such, <span class="highlighter">always treat the semicolon as a terminator (end of a rule) and not as a separator (merely separating two rules).</span>

For instance, imagine a developer decides to add a third property after <code>font-family</code> to the above CSS. If the semicolon after <code>font-family: 'Verdana'</code> is missing, the CSS code won't compile. Because the previous developer treated the semicolon as a separator, not as a terminator, and left it off, the developer adding to the new code must be sure to address the missing semicolon in order for it to compile correctly, as shown below:

<pre lang="javascript" line="1">
/* BAD - Missing semicolon breaks the code*/
p {
    color: #C0C0C0;
    font-family: 'Verdana'
    margin: 10px;
}

/* GOOD - Semicolon after every property*/
p {
    color: #C0C0C0;
    font-family: 'Verdana';
    margin: 10px;
}
</pre>

Hence, for the sake of consistency, clarity, and soundness of code, we consider adding semicolons to all the rules within a rule-set to be best practice.

<h3>Comment Your Code</h3>

We are all in a pursuit to write self-descriptive, clean, and legible code that can be understood by other developers without difficulty. Adding comments goes a long way in making our code more understandable for others as well as for ourselves. Apart from describing the rules, CSS comments also act as labels or qualifiers that make searching for specific functionality in a CSS file easier.

As the number of style rules keeps growing, maintaining a CSS file can become overwhelming. While many developers can readily remember their own selectors, any developers inheriting the CSS will find it very difficult to comprehend and navigate their way if the previous developer has not left any clues. Commenting your code provides adequate context to the developer and reduces the trouble of trying to make sense of it later.

The illustration blocks used in this chapter are good examples of using comments. Having the comments <code>/* BAD */</code> and <code>/* GOOD */</code> clearly demarcates the code and indicates the bad and the good code snippets.

<pre lang="javascript" line="1">
/* BAD */
html {
  background-color: #ffe5ff;
  font-family: sans-serif;
}

.static-block{
  position: static;
}

.fixed-block{
  position: fixed;
  right: 0px;
  top: 0px;
}

/* GOOD */

/*Page-wide Style Rules*/
html {
  background-color: #ffe5ff;
  font-family: sans-serif;
}

/*Styling for Static Block*/

.static-block{
  position: static;
}

/* Styling for Fixed Block*/
.fixed-block{
  position: fixed;
  right: 0px;
  top: 0px;
}
</pre>

Although comments are not mandatory for making CSS work, they are very helpful to the folks presently working on the code and those who will work on it in the future. Making your code self-explanatory is a good practice and benefits everyone on a team in the long run.

<h3>Avoid Inline Styling</h3>

Part of discussing CSS best practices also includes addressing concerns about some of the bad practices. One bad practice is the use of inline styling. If we recollect:

<ol>
<li>Inline CSS are style rules written directly inside HTML tags using the <code>style</code> attribute.</li>
<li>Internal CSS are style rules written inside the <code>head</code> section of an HTML page within the <code>style</code> tags.</li>
<li>External CSS are styles written in a separate document (with a .css extension) that is linked to HTML documents. The linking is done by adding a reference to the external stylesheet inside the <code>link</code> element within the <code>head</code> section.</li>
</ol>

This example shows inline styling:

<pre lang="javascript" line="1">
/* BAD */

<div style="position: fixed; border: 2px solid red; top: 0px; right: 0px; width: 500px; height: 50px">Fixed Block</div>
<div style="position: static; border: 2px solid green;">Static Block</div>
</pre>

Out of the three approaches, inline styling should be used as a last resort because it:

<ol>
<li>Defeats the purpose of having an external resource in the form of CSS in the first place.The purpose of having a stylesheet is to separate the styling aspects from the underlying HTML markup, but inline CSS makes it a part of that markup.</li>
<li>Goes against the concept of using a style-guide-driven approach. A developer may accidentally insert an inline style rule that is not part of the overall style guide and, thus, may violate the overall site design.</li>
<li>Takes precedence over both internal and external stylesheets.</li>
</ol>

The following snippet shows the correct practice:

<pre lang="javascript" line="1">
/* GOOD */

<div class="fixed-block">Fixed Block</div>
<div class="static-block">Static Block</div>
</pre>

Following this practice of separating CSS code from the HTML markup, we simply reference the appropriate CSS classes using selectors. This not only avoids clutter in the HTML document but also makes updating the style rules at one place (in the CSS file) easy.

<h3>Avoid Repeating Properties</h3>

Repeating CSS properties is a mistake that developers learn to avoid over time and through experience. If we wish to use a certain property for multiple selectors, creating a separate class is better than repeating the property over and over again. Let's look at an illustration highlighting this issue and the correct practice to follow:

<pre lang="javascript" line="1">
/* BAD */
.static-block{
    color: #0000FF;
    position: static;
}

.fixed-block{
    color: #0000FF;
    position: fixed;
}

/* GOOD */

.static-block{
    position: static;
}

.fixed-block{
    position: fixed;
}

.block-background-default {
    color: #0000FF;
}

</pre>

Instead of repeating the same <code>color</code> property in two class declarations, we can create a new class named <code>block-background-default</code> to render the blocks in default color (blue, in this case). This class can now be used in conjunction with any other existing classes.

<h2>Organization</h2>

This section talks about the best ways to organize our CSS and arrange the various CSS declarations for the sake of future maintenance of the site. Instead of haphazardly creating ids and classes in the order in which they are encountered, we can opt for a sound and coherent structure.

<h3>Modularizing Your CSS</h3>

The best way to organize your CSS is to separate related code in different files and import those files in a "master file." This approach not only avoids the problem of including too much code in a single file; it also logically separates the CSS. For instance, in the snippet below, we have split our CSS code into four files: <code>reset.css</code>, <code>header.css</code>, <code>content.css</code> and <code>footer.css</code>. We can import all these styles in the master CSS, as shown below:

<pre lang="javascript" line="1">
/* master.css */
@import url("reset.css");
@import url("header.css");
@import url("content.css");
@import url("footer.css");
</pre>

Each CSS file imported in the <code>master.css</code> serves a specific purpose:

<ol>
<li>The <code>reset.css</code> file contains a set of rules used to remove the browser's built-in styles. They are loaded before any other style rules to get around any browser inconsistencies in rendering the default styles. CSS Resets are discussed further later in this chapter.</li>

<li>The <code>header.css</code> file contains CSS related to the styling of the components that belong to the page header. For instance, the CSS to style any navigation bars, login component, company logo, search panel, or <a href="#" tabindex="0" id="popover-element" class="popover-element" data-toggle="popover" data-trigger="focus" data-placement="top" title="Breadcrumbs" data-content="A breadcrumb is a secondary navigation scheme that indicates the current page's location. An example of breadcrumbs is commonly seen while shopping online. A baseball bat will be located under Departments: Sports: Outdoor Sports: Baseball: Baseball Equipment: Baseball Bats. This trail is usually placed at the top of the page for visibility.">breadcrumbs</a> should be placed here.</li>

<li>The <code>content.css</code> file contains CSS related to the contents of the page. Styling for HTML elements, such as <code>section</code>, <code>article</code>, or <code>aside</code>, or for selectors used to target elements within the body of the page are placed here.</li>

<li>The <code>footer.css</code> file contains CSS related to the styling of the components that belong to the page footer.</li>
</ol>

The biggest advantage of this approach is that we can update the CSS for a particular element without any hassle. As the CSS is modularized into its respective files, overriding specific styles when necessary becomes easy, which makes editing the CSS a less tedious process.

Since the <code>master.css</code> consolidates all the required CSS resources, we can simply use the following code to import the CSS on our page:

<pre lang="javascript" line="1">
/* Import master.css */
@import url("master.css");
</pre>

<h3>Reusing Modules</h3>

Another major advantage of creating modules is the reusability of our code. If we wish to create a header with a different style for specific viewports, we can do this easily without disturbing any existing CSS code.

For instance, if we imagine we have a CSS file named <code>header_mobile.css</code> and wish to utilize it for viewports smaller than 320 px, media queries can be used to import this CSS file, as shown below:

<pre lang="javascript" line="1">
/* master.css */
@import url("reset.css");
@import url("content.css");
@import url("header_mobile.css")

/* More than 320px */
@import url("header.css") only screen and (min-width: 320px);

@import url("footer.css");
</pre>

<h3>Use a Block Structure</h3>

When we use a block structure, we group related style rules together. A good real-world example of block structure is a computer keyboard that has the alphabet keys together, the numeric keys in their own group, and the function keys lined up on the top. If the keys are randomly arranged, typing would become an ordeal because users would have a hard time locating the correct keys. Similarly, using a block structure is a good habit that keeps related rules together and prevents the hassle of having to search for a rule.

In the following example, the style rules related to a particular element/functionality are not grouped together, making the task of pinpointing the CSS code for debugging purposes tedious:

<pre lang="javascript" line="1">
/* BAD */

#navbar a:link {
  color: white;
  text-decoration: none;
}

html {
  background-color: #7BC143;
  color: white;
  font: 75% sans-serif;
  text-align:center;
}

#navbar a{
  border-right: 1px solid;
  color: inherit;
  display:inline;
  padding: 10px;
}

.reftext {
  font-size: 18px;
}

#navbar
{
  background-color: #D61F57;
  margin-left: auto;
  margin-right: auto;  
  width: 50%;
}

header{
  color: black;
  font-size: 150%;
}
</pre>

Let's fix this and make use of CSS comments to arrange our code:

<pre lang="javascript" line="1">
/* GOOD */

/* ********** Page-wide CSS styles ********* */ 
html {
  background-color: #7BC143;
  color: white;
  font: 75% sans-serif;
  text-align:center;
}

/* ********** HTML header element CSS styles ********* */ 
header{
  color: gray;
  font-size: 150%;
}

/* ********** Reference text CSS styles ********* */ 
.reftext {
  font-size: 18px;  
}

/* ********** Navigation bar related CSS styles ********* */ 

#navbar
{
  background-color: #D61F57;
  margin-left: auto;
  margin-right: auto;
  width: 50%;  
}

#navbar a{
  border-right: 1px solid;
  color: inherit;
  display:inline;
  padding: 10px;
}

#navbar a:link {
  color: white;
  text-decoration: none;
}
</pre>

As we can see, all the related rules are kept together, which makes reading and understanding the code simpler. Also, the rules are arranged in increasing order of specificity under a block. This makes it easy to locate any element on the DOM and relate it back to the CSS.

<div class="exercises-div">
<h4>Exercises</h4>

<strong>Rearranging CSS into Blocks</strong>
In this task, you will analyze the CSS and divide the rules into logical blocks. Keep all the related rules together and add comments to improve code readability.

The following snippet is a part of a larger CSS code. The selectors are all over the place; no grouping is used. We see no comments and none of the properties are alphabetically arranged. The focus of this task is not on the selectors and their properties but on the way the code should be organized.

<pre lang="javascript" line="1">
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

@import url("https://fonts.googleapis.com/css?family=Montserrat");

body {
    font-family: 'Helvetica Neue', Helvetica, sans-serif;
}

html,
body {
    height: 100%;
}

input#show-menu {
    position: absolute;
    opacity: 0;
}

#fix-bar {
    position: fixed;
    top: 0;
    left: 0;
    z-index: 9;
    width: 100%;
    height: 60px;
    background-color: #00a8eb;
}

#fix-bar .logo a {
    display: block;
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    line-height: 24px;
    width: 60px;
    height: 24px;
    padding: 18px 16px 18px 24px;
    box-sizing: content-box;
}


#fix-bar .logo {
    position: absolute;
    left: 0;
    width: 250px;
    transform: translate3d(-50%, 0, 0);
    transition: transform 0.5s ease;
}


#fix-bar .push {
    position: relative;
    left: 0;
    height: 100%;
    background-color: #00a8eb;
    transition: transform 0.5s ease;
}

#canvas {
    position: relative;
    height: 100%;
    padding-top: 60px;
    overflow: hidden;
}

#nav {
    overflow-y: scroll;
    position: absolute;
    left: 0;
    height: 100%;
    width: 250px;
    transform: translate3d(-50%, 0, 0);
    transition: transform 0.5s ease;
    padding-top: 12px;
    padding-bottom: 60px;
}

#nav .site-menu {
    position: relative;
    min-height: 100%;
    padding-bottom: 60px;
}

#nav a {
    text-decoration: none;
    color: #000;
    display: block;
    padding: 14px 24px;
    font: 20px/1 'Montserrat', sans-serif;
    font-weight: 700;
}

#nav a:hover {
    background-color: #eee;
}

#nav .copy {
    position: absolute;
    bottom: 0;
    padding: 16px 24px;
    font-size: 12px;
    line-height: 1.4;
}

input#show-menu:checked ~ #fix-bar .push {
    transform: translate3d(250px, 0, 0);
}

#content {
    background-color: #fff;
    overflow-y: scroll;
    position: relative;
    left: 0;
    height: 100%;
    transition: transform 0.5s ease;
    transform: translate3d(0, 0, 0);
    padding: 20px;
}

input#show-menu:checked ~ #canvas #content {
    transform: translate3d(250px, 0, 0);
}

.mask {
    position: absolute;
    top: 60px;
    left: 0;
    z-index: -1;
    width: 100%;
    height: 100%;
    opacity: 0;
    transition: opacity 0.5s ease, transform 0.5s ease, z-index 0s 0.5s;
    background-color: rgba(0,0,0,0.5);
}

input#show-menu:checked ~ #canvas #nav,
input#show-menu:checked ~ #fix-bar .logo {
    transform: translate3d(0, 0, 0);
}

input#show-menu:checked ~ #canvas .mask {
    z-index: 1;
    opacity: 1;
    transform: translate3d(250px, 0, 0);
    transition: opacity 0.5s ease, transform 0.5s ease;
}
</pre>

Refactor this CSS according to the specifications mentioned above.



</div>

<h2>Selector Naming Conventions</h2>

At the heart of successful CSS code writing is the use of self-descriptive names to create CSS selectors. Following best practices while creating and updating selectors contributes to clean and maintainable CSS. Let's look at some good habits with respect to constructing selectors.

Imagine that you run across a CSS class named <code>bar</code>, but you have no idea whether it refers to a navigation bar, a footer bar, or some other bar-like component on the page. This class name is not only generic; it gives the user no clue about its functionality. Comments do come to the rescue in such scenarios, but again, not everyone comments CSS code in detail. Hence, it becomes very important to use descriptive names and a naming convention while writing CSS.

<h3>Use More, not Fewer, Words</h3>

The basic rule of thumb is to use more words (ideally two to three) to describe a selector. This makes it self-descriptive. For example, <code>profile-avatar</code>, <code>profile-info</code> or <code>profile-menu</code>. This also helps avoid possible naming conflicts. Creating all three classes as simply <code>profile</code> would cause a conflict of rules.

<h3>Don't Label According to Color</h3>

Avoid naming based on color as such an arbitrary naming structure can lead to confusion later on. In the following example, the class name <code>.button-green</code> gives anyone reading the code an idea that the button will be green. If the color of the button happens to change to blue, the class name will inaccurately reflect the true color of the button:

<pre lang="javascript" line="1">
/* BAD */

.button-green {
    background-color: #00FF00;
    border: 1px solid #00FF00;
}

</pre>

To address this, the class name must be changed, a new class for the blue button will need to be created, or additional documentation must be provided to convey the real meaning of the button. To avoid this hassle, we can create a class with the name <code>.button-success</code>, a name that labels the use of the button without describing it:

<pre lang="javascript" line="1">

/* GOOD */

.button-success{
    background-color: #00FF00;
    border: 1px solid #00FF00;
}
</pre>

This class can be used to create a green-colored button or a button of any other color. If the specification for the class changes in the future, no new class needs to be created to accommodate this change.

<h3>Don't Name HTML Tags as CSS Selectors</h3>

Finally, to avoid confusion, do not name your selectors the same as the CSS type selectors. The following snippet shows an example of what not to do:

<pre lang="javascript" line="1">
/* BAD */
.div .span {
    color: #C0C0C0;
}

/* CORRESPONDING HTML*/
<div class="div">
    <span class="span">Container Text</span>
</div>
</pre>

The resulting HTML will create confusion because the tag names and the CSS class names are the same. The best practice is to use descriptive names to avoid naming chaos.

<pre lang="javascript" line="1">
/* GOOD */

.container .container-text{
    color: #C0C0C0;
}

/* CORRESPONDING HTML*/
<div class="container">
    <span class="container-text">Container Text</span>
</div>
</pre>

In the above snippet, we can clearly make sense of the structure by looking at the class names.

<h3>Minimize the Use of IDs</h3>

Best practices require that we avoid the use of CSS IDs unless absolutely necessary. IDs are more specific and they override other CSS rules because their specificity is higher than class selectors. ID selectors should only be used for unique elements on a page. Unless we are confident that a particular set of styling rules would be required only once on a page, use of IDs should be minimized in favor of CSS classes.

We can make use of CSS combinators (otherwise known as contextual selectors) along with the semantic HTML tags to create more meaningful layouts. Let's recap some of the combinators we discussed earlier:

<ul>
<li>The <strong>descendant selector</strong> selects all the elements that are descendants of a given element. For example, <code>#navbar a</code>.</li>
<li>The <strong>child selector</strong> selects the immediate children of the given element. For example, <code>section > header</code>.</li>
<li><strong>Sibling Selectors</strong>:
    <ul>
 <li>The <strong>general sibling selector</strong> selects siblings provided that they share a common parent and the second element is preceded by the first on the DOM. For example, <code>article ~ div</code>.</li>
 <li>The <strong>adjacent sibling selector</strong> selects siblings that immediately follow the given element. For example, <code>article + span</code>.</li>
    </ul>
</li>
</ul>

These declarations make our selectors more verbose and lengthy but also more self-explanatory. Combining contextual selectors with semantic HTML tags will also avoid the tendency to create IDs for every level in a nested <code>div</code> structure. Let's look at the following example to understand the usefulness of this practice:

<pre lang="javascript" line="1">

<div id="navigation">
    <div id="navigation-content">
    ...
    </div>
</div>

<div id="section">
    <div id="subsection">
        <div class="content">
        ...
        </div>
    </div>
</div>
</pre>

The above snippet does not make use of modern HTML tags, such as <code>nav</code>, <code>section</code>, and <code>article</code>. This results in creating an ID selector for every level of the nested structure, as shown:

<pre lang="javascript" line="1">
/* CSS */

#navigation{ ... }

#navigation-content { ... }

#section { ... }

#subsection { ...}

.content { ... }
</pre>

Instead, the new HTML5 tags should be used to create the nested structure, which will, in turn, reduce the number of CSS IDs used (like the ones preceded by # in the above examples). The following snippet shows the redesigned HTML structure:

<pre lang="javascript" line="1">

<!-- HTML -->
<nav id="navigation-content">
</nav>

<section>
    <article>
        <div class="article-content">
        ...
        </div>
    </article>
</section>
</pre>

<pre lang="javascript" line="1">
/* CSS */
#navigation-content { ... }

.article-content { ... }
</pre>

A navigation bar ideally appears just once on a web page. Hence, it can be uniquely styled using the <code>id</code> selector <code>#navigation-content</code> while the class selector <code>.article-content</code> formats the content within an article residing inside a section. This method makes the selector less specific and fully self-explanatory.

<h3>Combining Selectors</h3>

Whenever possible, combine selectors to avoid repeating style rules. This helps to reduce the size of the CSS code. Any specific property for a selector can be specified later.

In the following example, we combine rules for the <code>h1</code>, <code>h2</code>, and <code>h3</code> type selectors, but if we wish to write specific rules for <code>h3</code>, we must write it as a separate rule:

<pre lang="javascript" line="1">
/* BAD */

h1 {
    color: #C0B4F8; 
    font-family: 'Verdana';
}

h2 {
    color: #C0B4F8;
    font-family: 'Verdana';
}

h3 {
    color: #C0B4F8;
    font-family: 'Verdana';
}

/* GOOD */
h1, h2, h3 {
    color: #C0B4F8; 
    font-family: 'Verdana';
}

h3 {
    border: 1px solid #C0C0C0;
}
</pre>

This concludes our discussion on naming conventions involving selectors.

<div class="exercises-div">
<h4>Exercises</h4>

<strong>Refactoring CSS</strong>

In this task, the focus will be on the CSS selectors. We will work on a portion of the snippet used in the previous exercise and refactor it to include the best practices involving selectors. Consider the following HTML markup and corresponding CSS code.

<pre lang="html4strict" line="1">
<!-- HTML code -->
<div id="nav">
    <ul class="site-menu">    
        <li><a href="#/work">Work</a></li>
        <li class="has-sub"><a href="#/about">About</a></li>
        <li><a href="#/careers">Careers</a></li>
        <li><a href="#/news">News</a></li>
        <li><a href="#/contact">Contact</a></li>
        <li class="copy">© 2017 Logo. All Rights Reserved.</li>
    </ul>
</div>
</pre>

<pre lang="javascript" line="1">
/* CSS code*/
#nav {
    overflow-y: scroll;
    position: absolute;
    left: 0;
    height: 100%;
    width: 250px;
    transform: translate3d(-50%, 0, 0);
    transition: transform 0.5s ease;
    padding-top: 12px;
    padding-bottom: 60px;
}

#nav a {
    text-decoration: none;
    color: #000;
    display: block;
    padding: 14px 24px;
    font: 20px/1 'Montserrat', sans-serif;
    font-weight: 700;
}

#nav a:hover {
    background-color: #eee;
}

#nav .site-menu {
    position: relative;
    min-height: 100%;
    padding-bottom: 60px;
}

#nav .copy {
    position: absolute;
    bottom: 0;
    padding: 16px 24px;
    font-size: 12px;
    line-height: 1.4;
}
</pre>

Perform the following tasks on the above snippet:

<ol>
<li>Update the HTML code to use the native HTML <code>nav</code> tag instead of the <code>id="nav"</code> attribute.</li>
<li>Update the CSS code to dereference usage of the ID selector <code>nav</code> and use the type selector instead. Make the necessary changes to all the child elements as well.</li>
<li>Arrange all the properties alphabetically.</li>
<li>Create a new CSS selector for the <code>class="has-sub"</code> attribute. Add the following properties to it: font size of 12 pt with a transition effect of fade upon hover.</li>
</ol>

</ol>
</div>

<h2>Properties</h2>

CSS properties are the building blocks of all the selectors we create. Let's explore some handy practices that will help in better organizing properties.

<h3>Order Properties Alphabetically</h3>

When lines of text are ordered in some manner, we tend to process them more easily. This applies to CSS rules as well. Over time, the properties within a rule either keep adding up or get updated. It becomes increasingly difficult to keep track of the properties if there is no order to them. One way of organizing properties is by arranging them in alphabetical order. This not only helps us find a specific rule if we ever need to edit it later; it also avoids developers repeating rules.

In the snippet below, the properties for the <code>section-subheader</code> selector initially do not have a specific order:

<pre lang="javascript" line="1">
/* BAD */
.section-subheader
{
    background: #EFF5FB;
    padding: 10px;
    border: dashed 2px maroon;
    margin-bottom: 20px;
    width: 40%;
}

</pre>

However, sorting them alphabetically makes it easier to find a property later. A developer wanting to add a border to this selector will easily notice that the property already exists:

<pre lang="javascript" line="1">

/* GOOD */
.section-subheader
{
    background: #EFF5FB;
    border: dashed 2px maroon;
    margin-bottom: 20px;
    padding: 10px;
    width: 40%;
}
</pre>

While alphabetizing may not make much difference for a selector that has few properties within a rule, arranging them alphabetically does help when several properties are present. This practice of ordering properties alphabetically also indirectly influences the next developer working with the code to add new properties in the correct alphabetical order.

<h3>Minimize the Number of Properties</h3>

The fewer the properties, the cleaner and more efficient our CSS will be. Avoid adding a new property unless one is absolutely required. If a property is being repeated at several places, specify it at only one place in order to avoid redundant code. For this, we can use the inheritance feature of CSS to our benefit.

Let's look at an example in which we can avoid repeating properties if the selectors have a parent-child relationship.

<pre lang="javascript" line="1">
/* BAD */
.menu {
    background-color: beige;
    font-family: verdana;
}

.menu li {
    background-color: beige;
    display: inline-block;
    font-family: verdana;
    position: relative;
}

/* GOOD */
.menu {
    background-color: beige;
    font-family: verdana;
}

.menu li {
    display: inline-block;
    position: relative;
}
</pre>

The child elements (in this case, the <code>li</code> being a child of the element with <code>class="menu"</code>) inherit all the properties defined for the parent element (except the <code>background-color</code> element). Unless we need to override a certain style declaration for a child element, we should avoid defining it again. In the example above, defining <code>background-color</code> and <code>font-family</code> again for the <code>li</code> introduces repeated code.

The <code>background-color</code> property is not inherited because the default color is set to <code>transparent</code> for the child elements. As a result, the background color of the parent element, <code>.menu</code>, is visible for the child element, <code>.menu li</code>.

Free tools, such as <a href="https://unused-css.com/">Unused CSS</a> or <a href="https://github.com/oyvindeh/ucss">uCSS</a>, are available that will parse your HTML and CSS. These tools significantly reduce the number of style rules by deleting the unused rules and their properties, and this results in smaller CSS files.

<h3>Minimize the Use of <code>!important</code></h3>

The <code>!important</code> property was introduced to give developers the power to override style rules within a stylesheet. It interferes with a core CSS concept called <em>specificity</em> which we discussed in the <em>Mastering CSS</em> chapter. The specificity score helps the browser decide the exact selector that will be applied to an element when the browser is unable to decide the exact selector to be applied to an element in the DOM. Consider the following snippet, which has rules set up for the HTML <code>header</code> tag:

<pre lang="javascript" line="1">
header { 
    color: blue; 
}

header .page {
    color: red !important;
    font-size: 18px;
}

header #box { 
    color: green; 
    font-size: 15px;
}
</pre>

The header color is blue in all cases except when the class is <code>page</code> or the ID is <code>box</code>. Based on the specificity of the selector, the appropriate rule is selected.

The <code>!important</code> clause is applied at the property level, not at the selector level; giving the <code>color</code> property more importance than <code>font-size</code> within a selector. In fact, the rule having greater specificity, <code>header #box</code>, bows down to the <code>!important</code> clause. This clause should be used as scarcely as possible, primarily because it forcefully overrides any previously declared rules.

<div class="exercises-div">
<h4>Exercises</h4>

<strong>Refactor CSS properties</strong>

In this exercise, we will focus on refactoring CSS properties. The CSS code is provided below:

<pre lang="javascript" line="1">
html {
  font-family: Georgia;
  background-color: #ffe5ff;
}

.subheading {
  font-family: Georgia;
  text-decoration: underline;
  border: 1px solid;
}

#navBar ul li {
  display: inline;
  padding: 10px;
  border-right: 1px solid;
  color: orange;
}

#navBar ul li a:link {
  text-decoration: none;
}

#navBar ul li a:visited {
  text-decoration: none;
  color: orange;
}

#navBar ul li a:hover {
  text-decoration: none;
  color: black;
}

#navBar ul li a:active {
  text-decoration: none;
  color: orange;
}

input:checked {
  font-family: Georgia;
  font-size: 15pt;
  display: none;
}
</pre>

<ol>

<li>Combine multiple selectors into one.</li>

<li>Many properties are repeated across selectors; eliminate the redundant properties.</li>

<li>Ensure that the rules are alphabetically ordered.</li>


</ol>
</div>

<h2>Miscellaneous Tips</h2>

To make our CSS even cleaner and more efficient, we can leverage some externally available resources to our advantage. We can use freely available tools to validate our CSS, reduce the size of the CSS file, and help get around browser inconsistencies.

Let's look at some additional tips that will help us get the most out of our CSS to create maintainable stylesheets.

<h3>CSS Resets</h3>

Each browser has its own built-in way of rendering elements (i.e., its own, default stylesheets). This results in inconsistent layouts of web pages across different browsers. A CSS reset is a set of styles that are loaded to offset these default browser styles after they are loaded. It does this by providing general styles, which can be further modified by the developer. By doing this, a web page's consistent look and feel across all browsers is guaranteed.

A popular resource for generating a CSS reset is created by Eric Meyer and can be found <a href= "http://meyerweb.com/eric/tools/css/reset/">here</a>. The CSS reset code from his website is shown below. It is relatively unaltered and should be tweaked to suit project-specific requirements.

<pre lang="javascript" line="1">
html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, 
figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, 
footer, header, hgroup, menu, nav, section {
    display: block;
}
body {
    line-height: 1;
}
ol, ul {
    list-style: none;
}
blockquote, q {
    quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
    content: '';
    content: none;
}
table {
    border-collapse: collapse;
    border-spacing: 0;
}
</pre>

Use a CSS reset either by placing the source file link in your HTML file or by copying the whole CSS reset into your stylesheet.

CSS Reset is often confused with CSS Normalization. Although the purpose of both is fundamentally the same---creating a stable, cross-browser starting point for our CSS---the two approaches are philosophically different. CSS resets override the browser (or user-agent) styles to zero out as much as possible in order to create a stable foundation to build upon. CSS normalization, instead, addresses only the inconsistencies between user/agent styles and, in case of differences, chooses the most appropriate style. <a href= "https://necolas.github.io/normalize.css/">Normalize.css</a> is a widely used resource created by Nicholas Gallagher.

If we wish to preserve browser defaults, we should use Normalize.css. However, to "unstyle" everything and start with a blank canvas, we should use a CSS Reset. For example, when using a CSS Reset, elements like <code>h1</code> through <code>h6</code>, <code>em</code>, and <code>strong</code> appear without any predefined styles. A Reset will strip any styling from the elements so that the developer has more control of the CSS from the start.

On the other hand, Normalize.css applies a set of styles to each element to make them look consistent across all the browsers. For example, Normalize.css makes all the input elements have the same font. CSS Reset does not have pre-built styles, so inputs have different fonts (for instance, text input and textarea).<!--COMMENT; ROBIN: "so inputs have different fonts" I really think this could be better explained if followed by "have different fonts depending on..." As is, you just state that they have different fonts, but I suspect that they are actually sometimes the same out of coincidence, OR that the reset makes each specific one always the same (every CSS reset textarea has a very specific font?) Please be clear by finishing this explanation.-->.

<h3>Use Shorthand Notations</h3>

We can leverage the shorthand notation of CSS properties to further reduce the size of our code. Frequently used properties, such as <code>border</code>, <code>padding</code>, and <code>margin</code>, etc., can be represented by their shorthand notations. Let's look at a couple of these properties:

<pre lang="javascript" line="1">
/* BAD */
/* Expanded representation */
border-color: black;
border-style: solid;
border-width: 1px;

/* GOOD */
/* Shorthand notation */
border: 1px solid black;
</pre>

As shown above, instead of specifying three different properties to draw a border, we can easily consolidate them into a single line of code. The same applies to the CSS <code>padding</code> and <code>margin</code> properties as well:

<pre lang="javascript" line="1">
/* BAD */
/* Expanded representation */
padding-bottom: 2px; 
padding-left: 5px;
padding-right: 2px; 
padding-top: 1px; 

/* GOOD */
/* Shorthand notation */
padding: 1px 2px 2px 5px;
</pre>

For <code>padding</code>, <code>margin</code>, and <code>border</code> properties, the general rule for shorthand notation is:

<pre lang="javascript" line="1">
margin: top right bottom left;
OR
padding: top right bottom left;
OR
border: top right bottom left;
</pre>

If we know all four values for any of these properties for an element, as a best practice, we should combine them into a single line of code. We can also specify anywhere between one to four values in the shorthand notation. The following table shows the relationship between the number of values and the <code>margin</code> it affects. The same syntax works for <code>padding</code>, as well.

<table class="table-example">
<thead>
<tr>
<th><strong>Shorthand notation</strong></th>
<th><strong>Margins set</strong></th>
</tr>
</thead>
<tbody>

<tr>
<td><code>margin: 50px;</code></td>
<td>top, right, bottom, and left margins set to 50 pixels.</td>
</tr>

<tr>
<td><code>margin: 50px 20px;</code></td>
<td>
top, bottom margins set to 50 pixels.
left, right margins set to 20 pixels.
</td>
</tr>

<tr>
<td><code>margin: 50px 20px 40px;</code></td>
<td>top margin set to 50 pixels.
left and right margins set to 20 pixels.
bottom margin set to 40 pixels.</td>
</tr>

<tr>
<td><code>margin: 50px 20px 40px 30px;</code></td>
<td>top margin set to 50 pixels.
right margin set to 20 pixels.
bottom margin set to 40 pixels.
left margin set to 30 pixels.</td>
</tr>
</tbody>
</table>

<h3>Validate Your CSS</h3>

Another good practice is to validate your CSS code using the <a href = "https://jigsaw.w3.org/css-validator/">W3C CSS Validator</a>. This is a handy tool we can use to error-check our code and account for any missing semi-colons or curly braces.

<h3>Minify Your CSS</h3>

Pushing a large CSS file in your production code would require calling this resource every time a web page is rendered, resulting in an increase in page-load times. Instead, we can follow best practices by creating a compressed version of our final CSS code using tools such as <a href="https://cssminifier.com/">CSS Minifier</a> or <a href="http://csscompressor.com/">CSS Compressor</a>.

In the context of CSS, minification or compression means removing all unnecessary characters, such as spaces, new lines, and comments without affecting the functionality of the source code. It is an optimization technique used to reduce the size of code transmitted over the web. Let's run a code snippet, which we created previously in this chapter, through the minification process.

<pre lang="javascript" line="1">
/* CSS BEFORE MINIFICATION */

/* ********** Page-wide CSS styles ********* */ 
html {
  background-color: #7BC143;
  color: white;
  font: 75% sans-serif;
  text-align:center;
}

/* ********** HTML header element CSS styles ********* */ 
header{
  color: gray;
  font-size: 150%;
}

/* ********** Reference text CSS styles ********* */ 
.reftext {
  font-size: 18px;  
}

/* ********** Navigation bar related CSS styles ********* */ 

#navbar
{
  background-color: #D61F57;
  margin-left: auto;
  margin-right: auto;
  width: 50%;  
}

#navbar a{
  border-right: 1px solid;
  color: inherit;
  display:inline;
  padding: 10px;
}

#navbar a:link {
  color: white;
  text-decoration: none;
}
</pre>

The CSS code after minification is shown below.

<pre lang="javascript" line="1">
/* CSS AFTER MINIFICATION */

html{background-color:#7BC143;color:#fff;font:75% sans-serif;text-align:center}header{color:gray;font-size:150%}.reftext{font-size:18px}#navbar{background-color:#D61F57;margin-left:auto;margin-right:auto;width:50%}#navbar a{border-right:1px solid;color:inherit;display:inline;padding:10px}#navbar a:link{color:#fff;text-decoration:none}
</pre>

As seen above, the size of the CSS file has been drastically reduced. We used a CSS compressor with the highest available compression level. The input size was 698 bytes while the output CSS was 336 bytes, resulting in an overall compression of 107%. All the comments and spaces are removed and the readability of the code is compromised, but browsers have absolutely no problems reading a minified CSS file. Minification is encouraged just before we are ready to place the CSS file on the server.

<h3>Avoid Using Many Web Fonts</h3>

Fonts are a key aspect of web design and the development process. Web fonts have become a trend, with <em>Lato</em>, <em>Roboto</em>, and <em>Open Sans</em> gaining significant popularity as of late. Since this concept of web fonts is relatively new, developers usually import more than one font for fallback purposes.

Each imported web font is an additional resource (extra font file to be pulled in from a location on the web) and not all web fonts render text well. Depending on their load time, some fonts may affect the rendering time of the web page. A best practice is to use two or three web fonts with the last font being a commonly used font. This way, the browser creates a font fallback in the CSS that reverts back to the default in the case that the web fonts fail to load.

<h3>Using Vendor Prefixes</h3>

Some newly introduced CSS properties (such as Flexbox and CSS transitions) don't have built-in, standardized support across different browsers, and some properties have different implementations on older browser versions. To address this, vendor prefixes were added to these properties. These prefixes let a browser render its own version of a certain property until it is standardized. Commonly used prefixes are: <code>-webkit</code> (Chrome, Safari, and newer versions of Opera), <code>-moz</code> (Firefox), <code>-ms</code> (Internet Explorer), and <code>-o</code> (older versions of Opera).

A good example is the Flexbox property, which has undergone a few changes since its inception. For Firefox, the 2009 version used <code>display: box;</code>, the 2012 version used <code>display: flexbox;</code>, and the current version uses <code>display: flex;</code>. Now, IE10 only supports the 2012 version. To maximize support across different browsers, specific versions of these properties must be used along with their vendor prefixes. This requires much effort if we wish to do it manually.

Fortunately, tools, such as Autoprefixer, are available to us that automatically add vendor prefixes to our CSS code. These tools also remove prefixes that are not necessary and makes the CSS compatible with older browser versions. The best way to use Autoprefixer is by enabling it in CodePen. Once in CodePen, click the gear icon next to the CSS and select the option to enable Autoprefixer, as shown in the following image:

<img src="https://study.moderndeveloper.com/wp-content/uploads/2016/11/autoprefixer-option.jpg" alt="Autoprefixer in Codepen" />

As an illustration, let's look at a CSS code for Flexbox:

<pre lang="javascript" line="1">
/* Without Prefixes */
.topNavigation {
    background: navy;
    font-family: Georgia;
    list-style: none;
    
    /* Flexbox properties*/
    display: flex;
    justify-content: flex-end;
}

/* With Prefixes */

.topNavigation {
    background: navy;
    font-family: Georgia;
    list-style: none;
    
    /* Flexbox properties*/
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-pack: justify;
    -webkit-justify-content: flex-end;
    -ms-flex-pack: justify;
    justify-content: flex-end;
}
</pre>

Autoprefixer, as the name suggests, will analyze the properties that have different versions of vendor prefixes and automatically add them to the existing property. This increases the size of the CSS code, but it ensures that the property renders evenly across all browsers.

<div class="exercises-div">
<h4>Exercises</h4>
<ol>
<li>Minify CSS</li>
Minify the following piece of CSS using <em>CSS Minify</em> and <em>CSS Compressor</em>. Do you notice any difference in the minified output from the two tools? Record the metrics before and after minification and the overall percentage in reduction of the CSS size.

Make sure all the properties are alphabetically ordered before the minification process.

<pre lang="javascript" line="1">
html {
  font-family: Georgia;
  background-color: #ffe5ff;
  margin-left:20px;
}

.subheading {
  text-decoration: underline;
}

.beforeTranslate{
  border: 2px solid black;
  width: 500px;
  height: 50px;
  background-color: blue;
​    
}
.afterTranslate{
  border: 2px solid black;
  background-color: blue;
  color: white;
  width: 500px;
  height: 50px;
  transform: translate(20px,40px); /* Standard syntax */
  opacity: 0.7;
}

.beforeScale{
  border: 2px solid black;
  width: 100px;
  height: 50px;
  background-color: blue;
}

.afterScale{
  width: 50px;
  height: 50px;
  border: 2px solid black;
  transform: scale(4,2);
  margin-left: 100px;
  opacity: 0.7;
  background-color: red;
}

.beforeSkewX, .beforeSkewY, .beforeSkewBoth, .beforeRotateClockwise, .beforeRotateCounterClockwise,.beforeCombined{
  border: 2px solid black;
  width: 150px;
  height: 50px;
  background-color: orange;
}

.afterSkewX{
  border: 2px solid black;
  width: 150px;
  height: 50px;
  background-color: orange;
  opacity:0.7;
  transform:skewX(35deg);
}

.afterSkewY{
  border: 2px solid black;
  width: 150px;
  height: 50px;
  background-color: orange;
  opacity:0.7;
  transform:skewY(25deg);
}

.afterSkewBoth{
  border: 2px solid black;
  width: 150px;
  height: 50px;
  background-color: orange;
  opacity:0.7;
  transform:skew(35deg, 25deg);
}

.afterRotateClockwise{
  border: 2px solid black;
  width: 150px;
  height: 50px;
  background-color: yellow;
  transform:rotate(35deg);
  opacity: 0.7;
}

.afterRotateCounterclockwise{
  border: 2px solid black;
  width: 150px;
  height: 50px;
  background-color: yellow;
  transform:rotate(-1.57rad);
  opacity: 0.7;
}

.afterCombined{
  width: 150px;
  height: 50px;
  border: 2px solid black;
  transform: scale(4,2);
  margin-left: 100px;
  opacity: 0.7;
  background-color: red;
  transform: translate(20px, 20px) rotate(30deg) scale(2,2);
}

</pre>

<li>Add Vendor Prefixes</li>
Analyze the following snippet and add the required vendor prefixes. The browsers in consideration are Safari, Firefox, Chrome, and Internet Explorer.

<pre lang="javascript" line="1">
.accordion{
    transition: all .2s ease-out;
    transition-delay: 1s;

}

.transform-box{
    transform: translate(20px, 20px) rotate(30deg) scale(2,2);
    box-sizing: border-box;
    background: linear-gradient(orange, white);
    border-radius: 5px;
}
</pre>

</ol>
</div>

<h2>CSS Naming Methodologies</h2>

Collaboration and code sharing have become one of the most critical aspects of web development. Because it is likely that multiple developers will work on a code base, choosing a common naming convention is necessary. This will prove to be invaluable when new code needs to be written, when existing code needs to be reused, or when old code needs maintenance. New developers will not be afraid to change the old code if the naming methodologies are easy to follow.

CSS is no exception to this rule. In fact, CSS is the first to spiral out of control if multiple developers keep creating new classes without fully understanding the existing CSS code base. This results in duplication of styles, specificity problems, and incomprehensible code.

This emphasizes the need to have a simple, yet, robust naming convention while writing and maintaining CSS code. CSS is a glossary of shared lexicon between developers, and importantly, everyone must understand and use a common language when it comes to writing new CSS code or updating the current code base.

<h3>Maintainability and Scalability of CSS Code</h3>

We have stressed the need to write clean, modular, maintainable, and scalable CSS code throughout this chapter. To help us understand exactly what we mean by these terms, let's define them in the context of CSS:

<ul>
<li><strong>Clean</strong> CSS code is code that is easy to comprehend and work with. In an ideal situation, a developer who joins the team midway through the project should not have any trouble reading or understanding the existing CSS code. Practices, such as BEM, OOCSS, SMACSS, and ITCSS, help keep CSS clean, concise, and readable.</li>
<li><strong>Modular</strong> practices group related CSS code. All related CSS code should be placed together (in the same stylesheet) to better understand the relationship between the CSS classes and the HTML components. Imagine the mess if all the CSS classes related to styling buttons are scattered throughout the CSS code.</li>
<li><strong>Maintainable/Scalable</strong> CSS code is code that can be easily modified despite its complexity and code that reuses CSS constructs to enable scaling CSS by avoiding redundancy.</li><!--COMMENT; ROBIN: "enable the scaling of CSS by avoiding redundancy"? I don't follow. is scaling redundant CSS impossible? Does avoiding redundancy maybe make scaling CSS just more efficient?-->
</ul>

Many major companies across the globe are trying to solve the problem of CSS scalability and maintainability by means of proposing a consistent naming convention. Let's look at some of the proposed methodologies.

<h3>Block, Element, Modifier (BEM)</h3>

Known as <a href="http://getbem.com/">BEM</a>, Block, Element, Modifier is a CSS naming methodology developed by the team at Yandex and is used to arrange CSS classes in a modular fashion. This is done by using a strict naming convention to create these classes. BEM makes code-sharing easier, resulting in improved clarity and scalability of the code.

BEM is based on three core concepts: block, element, and modifier.

<h4>Block</h4>

A standalone component that encapsulates functionality and appearance. It holds meaning of its own. Some examples of blocks are listed below:

<ol>
<li>A vehicle</li>
<li>A button</li>
<li>A navigation bar</li>
</ol>

<h4>Element</h4>

A component of a block that does not hold any meaning on its own. Elements are semantically tied to the block and perform a specific function within that block. Some examples of elements are listed below:

<ol>
<li>A steering wheel</li>
<li>A submit button</li>
<li>A navigation bar item</li>
</ol>

<h4>Modifier</h4>

An entity that manipulates the appearance or behavior of the block. Some examples of modifiers are listed below:

<ol>
<li>A convertible</li>
<li>A red button</li>
<li>A blue-colored navigation bar</li>
</ol>

<h4>BEM Syntax</h4>

BEM defines a strict way to create blocks, elements, and modifiers:

<ol>
<li>Blocks are simply CSS classes defined using an appropriate name. For example, <code>block</code>.</li>
<li>Elements are denoted by two underscores prefixing the name of the element, preceded by the name of the block. For example, <code>block__element</code>.</li>
<li>Modifiers are denoted by two hyphens prefixed to the name of the modifier and preceded by the name of the block. For example, <code>block--modifier</code>.</li>
</ol>

To fully utilize the advantages of BEMA, we should keep the following recommendations in mind:

<ol>
<li>CSS classes, <strong>not</strong> IDs, are strictly used to define the entities.</li>
<li>Since BEM does not allow cascading, we cannot create elements of elements. For instance, <code>.block__element__element</code> is not allowed as per BEM rules.</li>
<li>The name of the block will always precede the names of the elements or the modifiers.</li>
</ol>

<h4>BEM Illustrations</h4>

Let's look at a couple of illustrations using BEM to reinforce our understanding of this methodology.

<h5>Navigation Bar Demo using BEM</h5>

Here, we'll explore an example where we write regular CSS code to create a navigation bar component and, later, look at what its BEM equivalent classes (<code>.navbar {}</code>, <code>.navbar__item {}</code>, and <code>.navbar--blue {}</code>) would look like. Consider this HTML navigation bar snippet, which we created in a previous chapter:

<pre lang="html4strict" line="1">
<!-- HTML -->
<ul class="topNavigation">
  <li><a href="#">Online Banking</a></li>
  <li><a href="#">Mobile Banking</a></li>
  <li><a href="#">Accounts</a></li>
  <li><a href="#">Loans</a></li>
</ul>
</pre>

The corresponding CSS structure includes the following CSS classes:

<pre lang="html4strict" line="1">
/* CSS */
.topNavigation {/* ... */ }
.topNavigation li {/* ... */ }
.topNavigation li a {/* ... */ }
</pre>

The same code in BEM would be transformed into:

<pre lang="html4strict" line="1">
<!-- HTML -->
<ul class="nav nav--blue">

<li class="nav__item">
  <a href="#" class="nav__link">Online Banking</a>
</li>

<li class="nav__item">
  <a href="#" class="nav__link">Mobile Banking</a>
</li>

<li class="nav__item">
  <a href="#" class="nav__link">Accounts</a>
</li>

<li class="nav__item">
  <a href="#" class="nav__link">Loans</a>
</li>

</ul>
</pre>

Now, according to BEM, the CSS classes would look like:

<pre lang="html4strict" line="1">
/* CSS */
.nav { /* ... */ }
.nav__item { /* ... */ }
.nav__link { /* ... */ }
.nav--blue { /* ... */ }
</pre>

As we can see, the need for cascading CSS selectors is eliminated as each entity performs its own function, depending on its type (block, element, or modifier).

The following embedded CodePen contains all of the above code:

[codepen_embed height="500" theme_id="20476" slug_hash="73f60055a2d792c1c04d3731155cc9da" default_tab="result" user="moderndeveloper"]See the Pen <a href='https://codepen.io/team/moderndeveloper/pen/73f60055a2d792c1c04d3731155cc9da/'>BEM Illustration 1</a> by Modern Developer (<a href='http://codepen.io/moderndeveloper'>@moderndeveloper</a>) on <a href='http://codepen.io'>CodePen</a>.[/codepen_embed]

The outer <code>ul</code> element is the parent block (denoted by <code>class="nav"</code>), which is the entity that contains the navigation items, or <em>elements</em> in BEM terminology. The navigation items are indicated by the <code>li</code> items (denoted by <code>class="nav__item"</code>).

Within the list items are the hyperlinks, which are, again, elements according to BEM. As previously mentioned as a word of caution, syntax like <code>.nav__item__link</code> is not allowed in BEM. Hence, we created a new entity with a CSS class of <code>.nav__link</code> to indicate a link within a navigation bar.

Finally, the <code>.nav--blue</code> is a modifier that is used to change the color of the navigation bar to blue.

<h5>Buttons Demo using BEM</h5>

In this use case, we created different versions of a button by applying a combination of CSS classes to the HTML elements. The CSS code is written using pure BEM constructs. The illustration embedded below shows the CSS code written according to BEM specifications and the corresponding HTML structure.

[codepen_embed height="600" theme_id="20476" slug_hash="52d6f9005e5a4e51a2ade995ca838d7b" default_tab="result" user="moderndeveloper"]See the Pen <a href='https://codepen.io/team/moderndeveloper/pen/52d6f9005e5a4e51a2ade995ca838d7b/'>BEM Illustration 2 - Buttons</a> by Modern Developer (<a href='http://codepen.io/moderndeveloper'>@moderndeveloper</a>) on <a href='http://codepen.io'>CodePen</a>.[/codepen_embed]

Since a button is the block entity in this scenario, we created a CSS class for the button block named <code>.btn</code>.

The button label (or text) is an active part of the button and cannot exist without its parent entity. Hence, we create a CSS class named <code>.btn__text {}</code> for the button text according to the rules of BEM. The HTML and the CSS code to create a simple button are shown below.

<pre lang="html4strict" line="1">
<!-- HTML -->
<a href="https://learn.moderndeveloper.com/" class="btn">
  <span class="btn__text">Standard Button</span>
</a>
</pre>

<pre lang="html4strict" line="1">
/* CSS */
/* Block */
.btn {...}
.btn__text {...}
</pre>

To easily create variations of this button, we wrote a few modifiers. We made three types of buttons---big, medium, and small---and assigned them CSS classes of <code>btn--big</code>, <code>btn--medium</code>, and <code>btn--small</code> respectively.

Similarly, we also created three different button colors to choose from. Since the color modifies the appearance of the block entity (button), it is recognized as a modifier in BEM. The three CSS classes for creating red, green, and yellow buttons are <code>.btn--red {}</code>, <code>.btn--green {}</code>, and <code>.btn--yellow {}</code> respectively. This gives us the leverage to generate any combination of buttons by simply using a combination of classes we created.

For instance, to create a big, red button, we make use of the following HTML code:

<pre lang="html4strict" line="1">
<a href="https://learn.moderndeveloper.com/" class="btn btn--big btn--red">
  <span class="btn__text">Big Red Button</span>
</a>
</pre>

To make a medium-sized button appear green, the following code is used:

<pre lang="html4strict" line="1">
<a href="https://learn.moderndeveloper.com/" class="btn btn--medium btn--green">
  <span class="btn__text">Medium Green Button</span>
</a>
</pre>

We have achieved several objectives in a single refactor of the CSS code using BEM.

<ul>
<li>We have avoided cascading since the elements are now isolated within blocks and are independent of each other.</li>
<li>Blocks, elements, and modifiers belonging to an element are grouped together, making the tracking of relationships within a block easier.</li>
<li>The CSS classes (or a combination of CSS classes) describe a particular entity. For instance, <code>class="btn btn--medium btn--green"</code> self-describes the button being medium-sized and green in color.</li>
<li>Modifying existing styles is made easier. Since each CSS class is an isolated entity, finding and manipulating classes becomes easier.</li>
</ul>

Before concluding our succinct discussion on BEM and jumping to the next section on scalable and modular CSS, let's weigh some pros and cons of using the BEM approach in our projects.

<h4>Pros and Cons of BEM</h4>

Every methodology has some inherent benefits, but as a popular saying goes, <span class="inlineQuote">Every coin has two sides</span>, and so does the BEM methodology. BEM comes with its fair share of flaws we should be aware of. Let's first look at some of the benefits of using BEM in our projects:

<ol>
<li><strong>Encapsulation of Code</strong></li>
The modern age demands the use of UI components that can be reused for different projects. BEM helps us achieve this objective. The CSS classes are isolated and the code is encapsulated. Hence, pulling out related code and moving it across projects becomes easier. For example, if an image gallery is used across a couple of projects, we can easily extract the related code and change the modifiers to suit the requirements. 

<li><strong>Scalability</strong></li>
Due to the descriptive nature of the CSS classes, creating new styles for an existing component or creating a totally new component becomes easier. Less time is spent on looking up existing CSS classes and maintaining the growing size of the CSS code base becomes easy.

<li><strong>Predictability</strong></li>
Another advantage of using BEM is the flat class structure it creates. The nesting of classes is not necessary, which keeps the selector specificity low and avoids specificity wars.

<li><strong>Suited for larger sites</strong></li>
As the project keeps growing, CSS code keeps growing too. BEM helps to keep naming clashes in check as no two entities can have the same name according to BEM. Neither does it allow nesting of classes, as we stated earlier. Thus, over the long run, BEM helps to keep the CSS code clean and conflict free. This way, creating new or editing existing CSS code does not accidentally style components in a wrongful manner.
</ol>

BEM's benefits far outweigh any of what might be perceived as its drawbacks, but let's look at some of them anyways.

<ol>
<li><strong>Learning Curve</strong></li>
Although BEM is not difficult to understand, it may be difficult to implement on a day-to-day basis. This is mainly because it takes a considerable amount of time to change our CSS habits. Since BEM does not permit nesting of elements, first-time users experience a major paradigm shift when writing code that does not involve the cascading of style rules.

<li><strong>BEM alone is not enough</strong></li>
BEM is not the answer to all the CSS-related problems. BEM needs to be combined with media queries, CSS preprocessors, and strict coding standards in order to fully utilize the advantages of BEM. 

<li><strong>Adhering to rules</strong></li>
BEM is a methodology, not a standard. A developer can break rules to suit a situation but doing so is not advisable. For example, consider the following snippet.

<pre lang="html4strict" line="1">
<li class="nav__item btn--green">
  <a href="#" class="nav__link">Online Banking</a>
</li>
</pre>

This is a legitimate example, but it completely violates the naming convention recommended by BEM. The recommendation to use modifiers belonging to one block for a different block is not written in stone, but doing so does not describe what's going on with the HTML code. Utilizing modifiers for different blocks might give us the desired result, but it makes the code confusing for other developers.
</ol>

Apart from BEM, other methodologies have gained attention in recent times. Some of the popular ones are Inverted Triangle CSS (<a href="https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture/">ITCSS</a>), Object Oriented CSS (<a href="http://oocss.org/">OOCSS</a>), and Scalable and Modular CSS (<a href="https://smacss.com/">SMACSS</a>). Readers are encouraged to explore these methodologies and compare the benefits and disadvantages of employing the above-mentioned alternatives. We will take a shallow dive into one more naming methodology, SMACSS, next.

This concludes our understanding of BEM. The following exercise will strengthen our understanding about BEM before we jump into SMACSS.

<div class="exercises-div">
<h4>Exercises</h4>

Similar to the illustrations wherein we converted the existing navigation bar created in the previous chapter, this exercise will deal with writing BEM compliant code for a project we created earlier.

<strong>Business Card CSS and HTML Code to BEM</strong></li>
The task here is to convert the fully completed HTML and the CSS code for the 3D Business Card to meet the requirements of BEM: 
<ol>
<li>Identify all the blocks and define CSS classes for it.</li>
<li>Note all the elements within the business card parent block entity and create appropriate CSS classes using the BEM naming convention.</li>
<li>Create two modifiers to apply unique formatting to the front and back of the card. </li></ol>

The final business card should look identical to the previously created business card, but the CSS code should obey the rules of BEM methodology.
<ol>
</div>

<h2>Scalable and Modular CSS (SMACSS)</h2>

Scalable and Modular CSS, or SMACSS (pronounced "smacks"), is a CSS framework developed by Jonathan Snook. It defines a set of best practices designed for building CSS that is easily understood, easy to extend, and avoids CSS specificity conflicts. Unlike other CSS frameworks, SMACSS does not have a library to download and install. The author describes it as "an attempt to create a consistent approach to website development with CSS." It is more like a "style guide" than a rigid CSS framework.

In SMACSS, more emphasis is placed on using classes but using IDs is also fine when required. Emphasis is also put on limiting the nesting of selectors as much as possible. The basis of the idea is the concept that CSS can be categorized as <strong>Base</strong>, <strong>Layout</strong>, <strong>Modules</strong>, <strong>States</strong>, and <strong>Themes</strong> for its rules. Organizing CSS around these broad categories and following naming conventions that comply to these categories makes CSS written with SMACSS readable and meaningful. This avoids class names that have arbitrary styles associated with them.

SMACSS ideology revolves around the concept of categorization. By categorizing CSS rules, we begin to see patterns. This helps us define better practices around each of these patterns. The five general categories rules are:

<ol>
<li><strong>Base</strong>: These are used for defaults like <code>html</code>, <code>body</code>, <code>a</code>, <code>a:link</code>, etc. This includes CSS resets, which should be written at the start of your main CSS.</li>
<li><strong>Layout</strong>: These divide a page into sections with elements like header, footer, and article.</li>
<li><strong>Modules</strong>: These are the reusable components in the design.</li>
<li><strong>States</strong>: These are used to describe the possible variations for each element (expanded, hidden, inactive).</li>
<li><strong>Themes</strong>: These define the appearance of layouts and modules, for instance, a color scheme or a typographic standard.</li>
</ol>

SMACSS offers a naming convention for each category but does not force us to strictly follow it. Developers are free to inherit the suggested naming convention or come up with their own. Let us look at the guidelines for each of these categories.

<h3>Base Rules</h3>

As the name suggests, base rules are used for defining the default styling of elements. Base rules are applied to an element by using CSS type selectors, descendant selectors, or child selectors, along with any pseudo-classes. It does not include any class or ID selectors. If we want a certain degree of default styling to indicate how a particular element should look across the page, this category is the best place to define it.

<pre lang="javascript" line="1">
html {
    font-family: 'Roboto';
}

body {
    margin: 0;
    padding: 0;
}

ul {
    font-size: 12px;
}

h1 {
    font-family: 'Courier';
}
</pre>

CSS Reset is another good example of adding base styles. Its sole purpose is to remove browser inconsistencies in heights, margins, padding, font sizes by defaulting them to certain values. Since base rules use CSS selectors, SMACSS does not recommend any particular naming convention for this category.

<h3>Layout Rules</h3>

Major and minor layout components exist in every design. If we recall the Atomic Design approach, atoms form the smallest level of components and organisms represent composite structures. For instance, the page header is a major component, while the company logo and login button are minor components. Every minor component will fall under the purview of a major component, such as a navigation bar or a login widget. This category of rules covers CSS related to major components. The minor components will be covered in the next category---modules.

The amount of reuse determines the nature of the layout component. If a large amount of repetition is observed, the component should be considered a candidate for a module. Ideally, a single use calls for the use of IDs, while multiple usages is a hint to create classes. Generally, a layout style will have a single selector (either an ID or a class). In addition, a style could be set to allow the layout style to respond to different factors.

<pre lang="javascript" line="1">
#header, #footer {
    width: 800px;
}

#footer {
    background-color: #D9D9D9;
}
</pre>

In cases where the higher-level layout must be tweaked (based on user preferences or the size of the viewport), we can add other layout styles. SMACSS recommends using either <code>l-</code> or <code>layout-</code> as prefixes to the selectors to indicate a layout rule.

<pre lang="javascript" line="1">
.image {
    float: left;
}

.image-description {
    float: right;
}

.l-flipped .image {
    float: right;
}

.l-flipped .image-description {
    float: left;
}
</pre>

In the example above, the <code>.l-flipped</code> class allows the position of the image and its description to be swapped. As we notice, using ID selectors is not mandatory, but if we ever decide to use them, they need to be specified in the Layout styles.

<h3>Module Rules</h3>

Modules are the crux of a web page. They include components, such as login widgets, navigation bars, image carousels, and so on. Modules should be conceptualized so that they can exist on their own. Moving a module around to different parts of the design should not result in breaking the layout.

With modules, we should avoid using IDs and element selectors, mainly because they are meant to be reused across the design. A module is likely to contain several elements, resulting in a natural tendency to use element and descendant selectors.

<pre lang="javascript" line="1">
.contactme > p {
    margin-left: 10px;
}

.contactme span {
    text-decoration: underline;
}
</pre>

This works fine when the <code>span</code> and <code>p</code> elements are styled exactly the same way every time the contact module is used. But if the requirements change over time, and we need to style multiple <code>span</code> elements differently within the module, element and descendant selectors will create a bottleneck. Let's have a look at how this could possibly happen.

<h5>Avoid Element Selectors</h5>

When we can reasonably predict what HTML elements will be used, element and descendant selectors are permissible. But as the scope of the project grows, attaching element selectors to module classes becomes a restriction. Let's look at the HTML and the partial CSS for the contact widget.

<pre lang="javascript" line="1">

<div class="contactme">
    <span>Email</span>
</div>

/* The Contact Me Module */
.contactme > span {
    padding-left: 20px;
    background: url(icon.png);
}
</pre>

Everything works fine until we decide to add a telephone number. We do not want the same icon to show up for the telephone entry. Using element and descendant selectors has put us in trouble. The solution is to use selectors that describe the situation as clearly as possible. We can make use of CSS classes to remove any ambiguity and increase the semantics of the elements to be styled.

The revised markup looks like this:

<pre lang="javascript" line="1">
<div class="contactme">
    <span class="contactme-email">Email</span>
    <span class="contactme-tel">Telephone</span>
</div>

/* The Contact Me Module */
.contactme-email {
    padding-left: 20px;
    background: url(email-icon.png);
}

.contactme-tel {
    padding-left: 20px;
    background: url(tel-icon.png);
}
</pre>

The more generic the HTML selector is (such as <code>div</code> or <code>span</code>), the more likely there will be a conflict. But if we foresee the possibility of requirements changing, we should stick to the more semantic CSS classes.

<h3>State Rules</h3>

A state-related rule overrides all other styles under the given circumstances. For instance, a button is either pressed or not pressed, a tab is either selected or not selected, an accordion is either expanded or collapsed, and so on. SMACSS recommends using <code>is-</code> as a prefix to the selectors to indicate a state-related rule.

<pre lang="javascript" line="1">
<div id="article" class="is-hovered">
    <div class="contactme">
        <span class="message is-error">Invalid input!</span>
        <span class="contactme-email">Email</span>
        <span class="contactme-tel">Telephone</span>
    </div>
</div>
</pre>

The outer <code>div</code> element has an <code>id</code> attribute on it. This indicates the specified <code>id</code> is a layout related style (as previously discussed) and the <code>is-hovered</code> class represents a hover state on that <code>div</code>. The inner <code>div</code> has a <code>span</code> tag under it that has a <code>message</code> module hooked to it. We can easily attach an <code>is-error</code> state to it.

State changes are represented in one of three ways:

<ol>
<li><strong>Class Name</strong>: The change happens when a class is added or removed, usually with JavaScript. The above mentioned scenario covers this use case.</li>
<li><strong>Pseudo-Class</strong>: The change happens to elements that are descendants or siblings of the element with the pseudo-class. The most commonly used pseudo-classes are <code>:active</code>, <code>:hover</code>, and <code>:focus</code>. CSS also contains structure related pseudo-classes, like <code>:first-of-type</code>, <code>:nth-child(n)</code>, and <code>:nth-of-type(n)</code>, etc. In addition to these,  a number of other UI-related pseudo-classes respond to interactions in form handling.

The default state does not come with a pseudo-class. We can define styles for pseudo-classes as a secondary state of the module.

<pre lang="javascript" line="1">
.button{
    background-color: #444;
}

.button:hover{
    background-color: #448;
}

.button:focus{
    background-color: #44B;
}
</pre>

If variations (or sub-modules in SMACSS terminology) of the button exist, we need to design pseudo-class states for these sub-modules as well.

<pre lang="javascript" line="1">
.button{
    background-color: #444;
}

.button:hover{
    background-color: #448;
}

.button:focus{
    background-color: #44B;
}

/* Warning button*/

.button-warning{
    background-color: #F22;
}

.button-warning:hover{
    background-color: #F44;
}

.button-warning:focus{
    background-color: #F66;
}
</pre>

</li>


<li><strong>Media Query</strong>: The change happens under a certain criteria, such as varying viewport sizes.</li>
</ol>

As a final takeaway, we should be aware of naming conventions when we encounter a state that is very specific and unique to a particular module. In cases where the state exists only for a given module, include the name of the module in the state class name. Furthermore, ensure that the state rule is placed in a block with the module and it is not placed anywhere else in the CSS.

<pre lang="javascript" line="1">

/*  Accordion-Style Rules Start */ 

.accordion {
    margin: 10px;
    background-color: #000000;
    ...
}

.is-accordion-collapsed{
    background-color: #FFFFFF;
}

/*  Accordion-Style Rules End */ 
</pre>

Although the name of the state class is a little longer, it is very descriptive and fully qualifies the collapsed state of the accordion.

<h3>Theme Rules</h3>

Theme rules define colors or typography across a site. Separating themes into their own set of styles allows them to be more easily modified. It also allows for those styles to be replicated to create alternate themes.

Similar to style rules, theme rules can override and affect base styles, such as font sizes, behavior of hyperlinks, border colors, and so on. They can affect the layout as well as states. For instance, the <code>message</code> module we created above needs to have the font in 10 point size. The default font specifications would be initially specified in the module, while the new size would be specified in the theme.

<pre lang="javascript" line="1">
// in modules.css
.message {
    font-family: 'Verdana';
}

// in theme.css
.mod {
    font-size: 10pt;
}
</pre>

<h3>Coupling CSS and HTML</h3>

In the material covered so far, we created several selectors and used them to select HTML elements and style them. As we continually add rules to our stylesheets, the connection between HTML and the underlying CSS keeps increasing. Let's look at the CSS snippet and infer some points about its correlation with the HTML markup:

<pre lang="javascript" line="1">
#article div {
    border: 1px solid;
    background-color: gray;
}

#article div h4 { 
    text-decoration: underline;
}

#article div ul {
    padding: 2px; 
}
</pre>

Looking at the CSS gives us a fairly good idea about the HTML structure; the element with <code>id="article"</code> is a container that has more than one section, having a heading and an unordered list. We can observe that the flow of our CSS selectors relies heavily on the HTML structure.

This approach would work fine for a smaller website and one which does not undergo frequent layout changes. But for larger websites having varied code requirements, the HTML structure is bound to undergo changes. This forces the developers to add more selectors, which in turn, adds more rules.

The second and the more important observation is the depth of HTML to which the selectors are applied. <em>Depth of Applicability</em> is the number of generations affected by a rule. For instance, the depth of applicability in <code>#article > div > h4</code> is the generations. The greater the depth of the HTML selectors, the higher the coupling between CSS and HTML.

Let's look at another example to understand the depth of applicability. The following snippet shows the HTML code for a simple navigation bar:

<pre lang="javascript" line="1">
<nav id="navbar">
<ul>
<li><a href="#">Our Motto</a></li>
<li><a href="#">Courses Offered</a></li>
<li><a href="#">Contact Us</a></li>
</ul>
</nav>
</pre>

The longest selector that can be written in CSS is <code>#navbar ul li a</code> which impacts four generations. Even if the selector is written as <code>#navbar a</code>, its depth is still four generations. The greater the depth, the greater the dependency on the underlying HTML structure. This is what strongly couples HTML and CSS, and it is what we would like to avoid. As a result, page components can't be moved and more duplication of code is possible.

Ultimately, each developer must decide to adopt as many of the best practices we've discussed here as possible. Some of them are optional (such as using BEM instead of SMACSS), and some of them need refining (CSS Reset script). Adopting them from the start of the project ensures that the CSS code evolves in a clean, concise manner. As Nicholas Gallagher rightly summarizes in his <a href="http://nicolasgallagher.com/about-html-semantics-front-end-architecture/">blog</a>:

<span class="inlineQuote">Anyone can rearrange pre-built "lego blocks"; it turns out that no one can perform CSS-alchemy.</span>

Well-maintained CSS (or HTML or JavaScript, for that matter) is evident when developers can confidently modify parts of the code while adhering to a commonly agreed standard and not break any other part of the project. The only way to appreciate these best practices is to put them in practice during our coding routine.

This concludes the discussion of some of the commonly adopted best practices in CSS. Let's apply this knowledge to a couple of scenarios in order to make our CSS code clean and easy to read.

<div class="exercises-div">
<h4>Exercises</h4>

<ol>
<li><strong>Navigation Bar CSS in SMACSS</strong></li>

We have already converted our CSS code for the navigation bar to be BEM compliant in the previous exercise. The concerned Codepen snippet is embedded below for reference.

[codepen_embed height="300" theme_id="20476" slug_hash="73f60055a2d792c1c04d3731155cc9da" default_tab="result" user="moderndeveloper"]See the Pen <a href='https://codepen.io/team/moderndeveloper/pen/73f60055a2d792c1c04d3731155cc9da/'>BEM Illustration 1 - Navigation Bar</a> by Modern Developer (<a href='http://codepen.io/moderndeveloper'>@moderndeveloper</a>) on <a href='http://codepen.io'>CodePen</a>.[/codepen_embed]

Use this CSS code and convert it using SMACSS principles. Create ID selectors to store layout-specific rules. Make use of class selectors to create modules. Identify the possible state changes in the functioning of a navigation bar and write state-related classes for the same. One example of a state change is the change in color upon hovering on a menu item.

Make sure you follow all the best practices discussed throughout the chapter to keep the CSS organized and readable.

<li><strong>Editing the Navigation Bar</strong></li>

As shown in the Codepen snippet, all the menu items are aligned from left to right. In this task, you will create layout style classes to flip the arrangement of menu items from right to left. Build on the CSS from the end of the previous task to accomplish this.
</ol>
</div>

<div class="project-div">
<h4>Project Assignment</h4>

This task involves looking back at all the CSS code you have written so far and making it adhere to the best practices discussed in this chapter. The project in consideration is your online portfolio, which we created at the end of the <em>Introduction to Responsive Design</em> chapter.

Use any of the CSS naming methodologies discussed above to refactor your CSS code. You are free to use BEM, SMACSS, or a combination of both. Make use of CSS Resets and CSS Normalization techniques. Make sure the properties are alphabetically ordered and that repeating properties are taken care of. If the names of the selectors are modified, ensure the appropriate changes are made to the HTML markup as well.

After this refactoring task, the portfolio should look and function exactly as before.
</div>
