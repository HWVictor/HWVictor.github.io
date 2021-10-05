# HWVictor.github.io

HWVictor.github.io is a static website made with [Jekyll](https://jekyllrb.com/) and [GitHub](https://github.com/) meant to store my **Blogs**

## /\_layouts

Contains the layouts that Jekyll will use to generate multiple pages

### default.html

The default layout with the footer, navigation and a link to the styling sheet. It is inherited by other layouts

### post.html

Inherits default.html and definesd the layout of each post (title, date, content)

## /\_posts

Contains the content of the blog posts written in markdown (.md)

## /about

Contains an index.html file that defines the layout and content for the about page, it inherits the default layout and adds a title and some text explaining the site with some permalinks to the websites of the tools I used (GitHub and Jekyll)

## /assets/images

Contains the image to be displayed in the home page

## /blog

Contains the layout of the blog page, which includes a title and a for loop for displaying each blog. It Inherits the default layout

## /css

Contains the main stylesheet that changes the colors, fonts and overall look of the website

## .gitignore

Makes git ignore the \_sites/ directory created by Jekyll. \_sites/ is cleared and regenerated each time the site is compiled so there is no need for git to keep track of its changes

## config.yml

Tells Jekyll to use kramdown to render markdown (.md) files and defines the layout of the permalinks

## index.html

The layout of the home page, it inherits from the default layout and adds a header, a paragraph and an image
