# kohicoffee

## About
A web development project of making a coffee menu.

## Objectives
- make a simple static website

## Goals
- make a simple static website
- learn basic HTML structures
- practice CSS principles

# notes:
- menu items:
  - (5) coffee items
  - (4) tea items
  - (6) food items
  - different sized cups in oz.

- theme:
  - cozy/home-y
  - browns and honey yellow
  - simple and readable font

- layout:
  - column layout

- design:
  - bolded headings for each category, background color for each section
  - dark text, light background
  - minimalistic logo design


### version 1.0

### created 4/10/2026

#### coding notes:
- <!DOCTYPE html> declaration defines that the document is an HTML5 document
- <html> is the root element of an HTML page
- <head> element contains information about the page such as the page title
- <title> element shows what the page is about shown in the top of the browser or on the tab of that page.
- <body> element includes everything that will be shown inside the main browser window.
- elements: the HTML characters inside the angled brackets
  - each element are usually composed of two tags: an opening tag and a closing tag
- Bullet Point Styles (pg 333; Jon Duckett)
  - With CSS, the 'list-style-type' property allows you to control the shapr or style of a bullet point (marker)
    - unordered list: none, disc, circle, square
    - ordered list: decimal, decimal-leading-zero, lower-alpha, upper-alpha, lower-roman, upper-roman
    - syntax: list-style-type: type;
- <div> element allow for common elements to be grouped together in one block-level box
- <meta> contains information about the web page. It tells search engine about the page, who created it, and whether or not it is time sensitive

#### good coding practices:
- always use <!DOCTYPE html> at the very start
- set the language for search engine purposes
- close all tags!! even if some closing tags are optional
- use meaningful semantic elements to provide organization and readability within the code
- avoid using inline styles. keep your station clear! organize one file for html and one for css. it makes the code maintainable.
- use a meaningful title and descriptive meta tags (crucial for SEO)
- use heading elements wisely. not every title is an h1 header.
- always use the right html elements
- always validate your code


##### resources:
- website: w3schools.com/html
- book: HTML & CSS: design and build websites by Jon Duckett (2011)
- book: Hello Web Design by Tracy Osborn (2021)

#### validation log:
- 4/15 (4)
  - warning: consider adding a 'lang' attribute to the html start tag to declare the language of the document
  - the character encoding was not declared. proceeding using windows-1252?
  - trailing slash on void elements has no effect and interacts badly with unquoted attribute values (line 6, column 5; to line 6, column 55)
  - the heading h3 follows the heading h1, skipping 1 heading level
  
