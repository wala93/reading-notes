# Structure
 HTML Describes
 the Structure
 of Pages
 In the browser window you can see a web page that features exactly
 the same content as the Word document you met on the page 18. To
 describe the structure of a web page, we add code to the words we want
 to appear on the page.
 
 *****************************************************************************************************************************************************************************
# Extra Markup

Since the web was first created, there have
been several different versions of HTML.
In 1998, a language called XML
was published. Its purpose
was to allow people to write
new markup languages.

# DOCTYPEs
Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using



<!-- -->
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters.


# ID Attribute

Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. 



***********************************************************************************************************************************************************************






# HTML layout

HTML5 is introducing a new set of
elements that help define the structure of
a page.
As with all HTML5 and CSS3 content, its usage is still
subject to change but it is already widely being used by web
developers and it is likely that you will want to use them

******************************************************************************************************************************************************************************
Traditional HTML
Layouts
For a long time, web page authors used <div> elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the <div> element in the structure of the page.

 **BUT**:
HTML5 introduces a new set of elements that allow you to divide up the
parts of a page. The names of these elements indicate the kind of content
you will find in them. They are still subject to change, but that has not
stopped many web page authors using them already.

*********************************************************************************************************************************************************************************

 The <header> and <footer>
 elements can be used for:
 
- A header or footer for an
  individual <article> or
  <section> within the page.
- The main header or footer
 that appears at the top or
 bottom of every page on the
 site. 
 
 
 Navigation
  -<nav>
 The <nav> element is used to
 contain the major navigational
 blocks on the site such as the
 primary site navigation.
 
 
- <article>
 The <article> element acts as
 a container for any section of a
 page that could stand alone and
 potentially be syndicated.


-<aside>
 TheThe <aside> element has two
 purposes, depending on whether
 it is inside an <article>
 element or not.
 
 
 -<section>
 The <section> element groups
 related content together, and
 typically each section would
 have its own heading.
 
 
- <hgroup>
 The purpose of the <hgroup>
element is to group together a
set of one or more <h1> through
<h6> elements so that they are
treated as one single heading. 



Figures
-<figure> <figcaption>
You already met the <figure>
element It can be used
to contain any content that is
referenced from the main flow of
an article (not just images.
