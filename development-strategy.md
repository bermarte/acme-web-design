# Development Strategy

> `acme-web-design`

write a short description of your project:

Following the tutorial provided we have to rebuild a website containing 3 pages, each on a branch. For every branch we need to create a pull request to the master and merge it later with the master. The foundation and preliminary preparation of this exercise consists of writing and developing a clean development strategy and creating a wireframe.

- who would want to use it?  

This is a starter project for a beginner, it covers semantic HTML and CSS. We learn how to work with branches, how to develop a strategy to build this and future projects.
- why would they want to use it?  

A junior developer should understand how to work in team and how to work following a proper development strategy.
## Wireframe

<!-- include a wireframe for your project in this repository, and display it here -->
<!-- wireframe.cc is a good site for getting started with wireframes -->
![wireframe]()

## Step 0: Create a public repo on GitHub

### Repo

1. On GithHub create this repo
1. Generate from Template
1. Write initial, basic README
1. Write initial, basic development strategy
1. Turn on GitHub Pages
1. Clone this repo locally

### Steps to follow
1. locally, make a new branch  
   `git branch branch_name`
2. Switch to the new branch  
  `git checkout branch_name`
3. Add the branch_file to your local repository (Staging)  
   `git add file_name`
4. commit the changes  
  `git commit -m " message"`
6. switch to the master branch  
  `git checkout master`
7. repeat 1. for every branch  


### Repo

what branch(es) did you work on?
- master 
- css
- imgs
- index  
- about  
- services

### HTML

what did you change in the HTML and why?

### CSS
what did you change in the HTML and why?
* I have changed the nav of the home page to prevent changing the width of neighbouring links during hover  
[css-tricks](https://css-tricks.com/bold-on-hover-without-the-layout-shift/)  
[codepen.io](https://codepen.io/hexagoncircle/pen/WNrYPLo)  

* Once the first change was done, I have used Flexbox to fix the orizontal alignment of the elements in the nav

* I have tried to give the same width to the input fields and the button of the form contained in services.html when the width of the browser is less or equal to 768 pixels; once they have the same width they are visually more appealing.

## Finishing Touches

- Write final, complete README:
  - [makeareadme.com](https://www.makeareadme.com/)
  - [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
  - [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- Validate code to check for any last mistakes
