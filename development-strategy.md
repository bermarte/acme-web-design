# Development Strategy

> `acme-web-design`

write a short description of your project:

Following the tutorial provided we have to rebuild a website containing 3 pages, each on a branch. For every branch we need to create a pull request to the master and merge it later with the master. The foundation and preliminary preparation of this exercise consists of writing and developing a clean development strategy and creating a wireframe.   

[GO TO THE README](README.md)

- who would want to use it?  

This is a starter project for a beginner, it covers semantic HTML and CSS. We learn how to work with branches, how to develop a strategy to build this and future projects.
- why would they want to use it?  

A junior developer should understand how to work in team and how to work following a proper development strategy.
## Wireframe

<!-- include a wireframe for your project in this repository, and display it here -->
<!-- wireframe.cc is a good site for getting started with wireframes -->
![wireframe IMG](img/traversy_wireframe.png?raw=true)   
![wireframe PDF](Wireframing_acme.pdf)

## Step 0:
* Read the text of the assignment
* follow the tutorial step by step
* create a wireframe for the project by reverse-engineering the tutorial

### Repo

1. On GithHub create this repo
1. Generate from Template
1. Write initial, basic README
1. Write initial, basic development strategy
1. Turn on GitHub Pages (https://bermarte.github.io/acme-web-design/)
1. Clone this repo locally

### Steps to follow

1. locally, make a new branch  
   `git branch branch_name`
2. Switch to the new branch  
  `git checkout branch_name`   
   copy the files for that branch and add the HYF template to check the code later   
3. Add the branch_file to your local repository (Staging)  
   `git add file_name`
4. Commit the changes  
  `git commit -m " message"`
6. Switch to the master branch  
  `git checkout master`
7. Repeat 1. to 6. for every branch


### Repo

what branch(es) did you work on?
- master 
- css
- imgs
- index  
- about  
- services

8. On your client, chekout one branch at the time   
 `git checkout branch_name`
9. Push it to this repository creating the branch on the server     
 `git push --set-upstream origin branch_name`
10. Compare, create a pull request on GitHub, write a message, merge and confirm
11. Repeat 8. to 10. for every branch
12. On GitHub, continue writing the Development strategy (this file) 
13. Using githubpages, validate and debug the html files, the CSS and the rest using the template of HYF
14. Pull master to local
15. Fix the errors found at 13. on your local computer
16. Once finished push the changes to the server

### HTML

what did you change in the HTML and why?
* Removed the class on the button contained in services.html to style it better

### CSS
what did you change in the HTML and why?
* I have changed the nav of the home page to prevent changing the width of neighbouring links during hover  
[css-tricks](https://css-tricks.com/bold-on-hover-without-the-layout-shift/)  
[codepen.io](https://codepen.io/hexagoncircle/pen/WNrYPLo)  

* Once the first change was done, I have used Flexbox to fix the orizontal alignment of the elements in the nav

* I have tried to give the same width to the input fields and the button of the form contained in services.html when the width of the browser is less or equal to 768 pixels; once they have the same width they are visually more appealing.

* input edges and buttons are now squared like in the video, I like them more like that   

## Finishing Touches

- Write final, complete README:
  - [makeareadme.com](https://www.makeareadme.com/)
  - [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
  - [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- Validate code to check for any last mistakes
