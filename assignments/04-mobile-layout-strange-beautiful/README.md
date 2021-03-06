#CSS + SCSS + Mobile-First Responsive Layouts

##Description
Simple & Beautiful is an archive of interesting works combined from several artists' feeds. We are tasked with the assignment of building a responsive, static site on mobile, mid-sized, and large-sized screens.

<hr>
##Objectives

###Learning Objectives

After completing this assignment, you should be able to create a responsive, mobile-first layout.

###Performance Objectives

You should:
- use media-queries with `min-width` breakpoints  
- use the inline-block technique for aligning columns
- use fluid widths (%) on columns so that they dynamically adjust to screen width
- make use of SCSS features:  variables, mixins, and nesting
- be mindful of margin and padding and when/where to use them

##Deliverables 
- an `index.html` file with the content

- a project that compiles SCSS to CSS.
  - there should be a `main.scss` in a `/scss` folder
  - all the SCSS should compile to `styles.css` in a `css` folder
  - the `index.html` should link to the `styles.css` file

- a site that has a responsive layout for
  - mobile (< 768px)
  - tablet (768px - 1024px)
  - desktop (> 1024px)

- a Github repository and a live static site on Github Pages. 

<hr>

##From the Designer
###The mobile layout
![mobile](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/04-mobile-layout-strange-beautiful/mockup/sb-mobile.png)

<hr>
###The tablet layout
![tablet](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/04-mobile-layout-strange-beautiful/mockup/sb-tablet.png)

<hr>
###The full-screen layout
![full](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/04-mobile-layout-strange-beautiful/mockup/sb-desktop.png)

<hr>
##Additional
####The images
[link to zip file](https://github.com/TIY-Charleston-Front-End-Engineering/Course-Guide/blob/master/assignments/04-mobile-layout-strange-beautiful/images.zip)

####To Configure SCSS
1. Create a `scss` directory and create a `main.scss` file within. 
2. From the project's root directory, run: 
  ```
  sass --watch scss/main.scss:css/styles.css
  ```
3. Do your styles in the `/scss/main.scss` file, ideally taking advantage of SCSS features.
4. When you save your `main.scss
5. Open a new tab in your terminal (one tab for watching, another tab for navigating and operating on your file system)
6. `ctrl` + `C` will stop the SCSS watcher


####Apply the style rule `box-sizing: border-box` to *all* elements

```css
* {
    box-sizing: border-box
}
```

The font stack for the project is: Helvetica Neue, Helvetica, sans-serif


###Adventure Mode
Create a menu that appears on hover for the desktop version.
![adventure mode](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/04-mobile-layout-strange-beautiful/mockup/sb-adventure-mode-hover-menu.gif)

###Epic Mode 
Create a menu whose display toggles on click for the mobile version.
![epic mode](https://raw.githubusercontent.com/TIY-Charleston-Front-End-Engineering/Course-Guide/master/assignments/04-mobile-layout-strange-beautiful/mockup/sb-epic-mode-toggle-menu.gif)
