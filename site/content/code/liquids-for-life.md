---
title: Liquids For Life Website
date: 2019-02-28T21:49:59.117Z
repo: lfl
demo: 'https://lfl.stelabr.com'
tags:
  - javascript
  - react
  - react-router
  - markdown
  - webpack
  - bulma
  - css
  - html
---
For a long time I made my own kombucha. Friends would ask me how they could start making their own batches and eventually I realized it would be easier to make a website explaining the process. In early 2018 this idea turned into Liquids for Life. Conceptually, this website is all about providing distilled, easy to understand information about creating healthy beverages at home in order to provide alternatives to soda and alcohol.

Even though this website really should be a simple static site, I decided to try my hand at making a React app instead. I used React-Router to control the navigation.

This site is built in an interesting way. I use the raw file loader plugin for Webpack to turn markdown into a javascript value, then I use `markdown-it` to turn that into html. I have a `data.js` file that is a record of what markdown pages correspond to which section of the website. 

For styling, I used the wonderful CSS framework Bulma to provide the groundwork while adding a bunch of finishing touches myself.
