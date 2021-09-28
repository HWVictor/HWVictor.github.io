# HWVictor.github.io

HWVictor.github.io is a static website made with [Jekyll](https://jekyllrb.com/) and [GitHub](https://github.com/) meant to store my **Blogs**

## /\_layouts

Contains the layouts that Jekyll will copy to each page

### default.html

The default layout with the footer, navigation and a link to the styling sheet. It is inherited by other layouts

### post.html

Inherits default.html and adds a title and a date to each post

## /\_posts

Contains blog posts written in markdown (.md)

## /about

Contains an index.html file that defines the layout and content for the about page, it inherits the default layout and adds a title and some text explaining the site with some permalinks to the websites of the tools I used (GitHub and Jekyll)

## /assets/images

Contains the image to be displayed in the home page

## /blog

Cotains the layout of the blog page, which includes a title and a for loop for displaying each blog. It Inherits the default layout

## /css

Contains the main stylesheet that changes the colors, fonts and look of the website

## .gitignore

Makes git ignore the \_sites directory created by Jekyll since I am not using Jekyll plugins that are not supported by GitHub pages

## config.yml

Tells Jekyll to use kramdown to render markdown (.md) files and defines the layout of the permalinks

## index.html

The layout of the home page, it inherits from the default layout and adds a header, a pargraph and an image
