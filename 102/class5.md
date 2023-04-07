# Read: 05 - Design web pages with CSS

What is the purpose of CSS?

- to style and layout web pages

What are the three ways to insert CSS into your project?

- External CSS.
- Internal CSS.
- Inline CSS.

Write an example of a CSS rule that would give all <p> elements red text.


Can the students give you the WHY, WHAT, HOW? Collect their responses on the whiteboard.

CSS is Cascading style sheets
used for STYLING your HTML
A lot of different selectors
inline CSS ←– Bad practice

external ← best way
internal <- Ok with single-page/ quick websites, but not preferred 
inline <- no no

Link your stylesheet in your <head> section
“reset sheet” ← you’ll learn this in 201

p {
color: blue;
}

p{color: blue;}



<h1 class=”title”> My Titlte </h1>

<img id=”hero” src=”mypicture.jpg” alt=”this is my picture”>


.title{}

#hero{}

section p{
color: green;}

section, p{
color: green}



