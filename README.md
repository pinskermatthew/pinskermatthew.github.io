# pinskermatthew.github.io
This repository contains Matthew Pinsker's professional technical writing portfolio.

## About the website
The website is coded using a mobile-first approach. Default CSS is written for mobile devices. To write CSS for larger viewports, use `@media` queries.

## Layout
The website uses flexbox to lay out each page.

To learn more about flexbox, see [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/).

## Classes

`.container` = Use this class in `<div></div>` tags that nest other `<div></div>` tags. This class adjusts the width of each section.

`.main-info` = Use this class to define the **flex container** and **flex direction** for the navigation menu and `.about-me`/`.skills` combined section.

`.col` = Use this class in `<div></div>` tags nested in the `.main-info` container to adjust column width (in this section only).

`.hide` = Use this class to hide sections that are not ready to publish.

## IDs

### Jump Links
To create links that jump to specified sections on the page:

1. Add span tag tags nested inside of the section you want to jump to: `<span id="ID-NAME"></span>`.
**Example:**
```
<h2><span id="writing"></span>Writing Samples</h2>
```
2. Add anchor tags with its href attribute: `<a href="#ID-NAME"></a>`.
**Example:**
```
<a href="#writing">Writing</a>
```