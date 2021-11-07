# Natours
Natours project is **one** of the three projects built on design made by Jonas Schmedtmann.     

Natours is booking app for adventurous people who are seeking escape from everyday life to make exciting memories for their whole life. Users can see which tours are offered, reviews from users that have been on the tours and book the tour they wish to experience.

This project is done without any usage of flexbox or grid.

In the next sections I will be breaking down the things that have been shown in separate project sections, starting from general project settings until writing media queries for responsive design.


## Disclaimer

I am not the owner of page design. For any question about using the page design in commercial purposes, contact Jonas Schmedtmann.

## General project settings

- Setting up the basic reset using **universal selector**
- Setting up project-wide font definitions
- Implementing **BEM methodology ( Block Element Modifier )** inside our project ( http://getbem.com/introduction/ )
- Installing **Node.js, NPM and Sass**
- Initiating **npm** inside our project
- Installing **npm packages** for our project ( *sass, autoprefixer, concat, npm-run-all, postcss-cli, postcss* )
- Installing **live-server** for automatic reload of our page on any change in code
- Writing **npm scripts** for automation
- Writing **Sass variables**
- Implementing **7-1 CSS Architecture** ( https://www.learnhowtoprogram.com/user-interfaces/building-layouts-preprocessors/7-1-sass-architecture )
- Writing simple build proces with npm scripts
- How to use **:selection** property

## Header ( Hero ) section

- Using **clip-path** for clipping parts of the element ( creating beautiful background image in this case )
- Using **transform, left, top** for easy centering  
- Creating CSS animations using **@keyframes** and **animation** property
- Learning about **pseudo-classes** and **pseudo-elemnts** and how to use them
- Creating hover animations using **transition** property

## Building float layout

- How to build and architect grid system using **float**
- How **attribute selector** works
- How **:not** pseudo-class works
- How **calc()** works

## About section

- How and when to use **utilites** classes
- How to use **background-clip** property
- How to use **transform** on multiple properties simultaneously
- How to use **outlie-offset** and **outline** together
- How to style elements that are NOT hovered while others are

## Features section

- How to include and use **icon font** ( https://github.com/linea-io/Linea-Iconset )
- How to create **skewd by using transform:skew()** background image
- How and when to use **direct child** selector

## Tours section

- How to build rotating card efect
- How to use **perspective** property
- How to use **backface-visibility** property
- How to use background blend modes
- How and when to use **box-decoration-break**

## Stories section

- How to use **shape-outside** and **float** to make text float around the given shape
- How to apply **filter** to images
- How to make a video cover entire background of a section
- How to use **video** HTML element
- How and when to use **object-fit** property

## Booking section

- How to implement solid-color gradients
- How the **general** and **adjacent** sibling selectors work
- How to use **::input-placeholder** pseudo-class
- How and when to use **:focus, :invalid, :pseudoholder-shown** and **:checked** pseudo-classes
- How to build custom radio buttons

## Footer section

- How to build simple footer for a webpage

## Navigation

- What is and how the **checkbox-hack** works
- How to use **cubic-bezier curves** for creating custom animation timing functions
- How to animate solid-color-gradients
- How and why to use **transform-origin** property

## Popup

- How to build popup window using only CSS
- How to use **:target** pseudo-class
- How to create equal-height boxes with **display: table-cell**
- How to create CSS text columns using **column-count** and **column-gap**
- How to automatically hyphenate words using **hyphens**

## Responsive design

- How to use Sass **mixins** to write CSS media queries
- How to use **@content** and **@if** Sass directives
- How to use Chrome **devtools** for responsive design
- How to use **@supports** feature queries
- How to use **backdrop-filter** property
- Why to use **only screen** on media queries
- Why to use **hover:none** as a condition in media queries

### Responsive images

- How to use **srcset** attribute with HTML elements **img** and **source** together with density descriptor
- How and why to use **picture** HTML element for art direction
- How to write meda queries in HTML
- How to allow browser to decide the best image to download using **srcset** attribute width descriptors and **sizes** attribute of the img HTML element
- How to implement responsive images in CSS
- How to use resolution media queries to target high-resolution screens
- How to combine multiple conditions in media queries



## Personal changes ( not covered in course )

- Added button with **back-to-top** functionality ( using jQuery )
- Added functionality to all buttons 
- Added functionality to navigation links ( every link leads to corresponding part of the page )
- Added smooth scrolling
- Added auto-hide to navigation when the user clicks on an item ( using jQuery )
- Added few links to outside pages
