# NextJS Blog

This is the completed result from this tutorial  [Next JS Tutorial](https://nextjs.org/learn/basics/create-nextjs-app).

## Table of contents

- [Overview](#overview)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Continued development](#continued-development)
- [Useful resources](#useful-resources)

## Overview

![](nextjs-blog.desktop.png)

### Built with

- next
- react

### What I learned

- If you need to add attributes like, className, add it to the a tag, not to the Link tag.
- Similar to render props pattern - uses Context API behind the scenes ?

- To add a global stylesheet, import the CSS file within pages/_app.js
- You cannot import global CSS anywhere else.

- Next.js has support for Image Optimization by default
- <Head> is a React Component that allows you to modify the head of a page.
- If you want to customize the <html> tag, for example to add the lang attribute, you can do so by creating a pages/_document.js file.
- next/script simplifies loading third-party scripts
- Next.js has built-in support for styled-jsx
- To use CSS Modules, the CSS file name must end with .module.css.
- classnames is a simple library that lets you toggle class names easily
- Out of the box, with no configuration, Next.js compiles CSS using PostCSS.
- Before you can use Next.js' built-in Sass support -> npm install -D sass
- Hydration: when a page is loaded by the browser, its JavaScript code runs and makes the page fully interactive.
- Your app is rendered without JavaScript
- The difference between Static Generation and Server-side Rendering is when HTML for a page is generated.
- YAML Front Matter can be parsed using a library called gray-matter.
- Next.js polyfills fetch() on both the client and server. You don't need to import it.
- getStaticProps runs server-side
- TTFB: Time to First Byte

- Anyway to get rid of constant SessionStorage warnings?

- Tutorial should have avoiding using dangerouslySetInnerHTML.
- Typescript -> you need to use arrow functions. 

- Remix is NextJS's closest competitor.  

### Useful Resources

- [NextJS](https://nextjs.org/learn/excel/typescript) - convert to typescript tutorial
- [Medium](https://medium.com/@anotherplanet/git-tips-next-js-github-pages-2dbc9a819cb8) - deploy next to github pages
- [Blog](https://luxiyalu.com/how-to-disable-nextjs-warning/) - disable nextjs warnings
- [Stack Overflow](https://stackoverflow.com/questions/56871384/what-is-the-difference-between-ts-and-tsx-extensions-both-are-used-as-extensi) - ts vs tsx