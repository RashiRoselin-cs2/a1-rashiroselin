Assignment 1 - Hello World: Basic Deployment w/ Git, GitHub, Render
===

*DUE: Friday, August28, 2025 by 1:59 PM*

First assignment! You will deploy the starting Web site that you will use this term to [Render](https://www.render.com/). 

Treat this assignment as a chance to get up to speed on Git, GitHub, and Render, as well as experiment some with HTML/CSS/JS.

**AI POLICY REMINDER:** You must adhere to the AI policy described in the course syllabus, including citations of any AI tools you used and how you used them.

Assignment details
---

This assignment requires that your website is both contained in a GitHub repository and hosted in Render.

### Clone to computer, push to Github, import to Render (recommended)

1. Fork the starting assignment code in GitHub. This repo contains the following:
    * The server code, `server.js`
    * A starting `index.html` file that you will edit as described below
    * A package.json file that helps configure Render
    * This README
2. Edit `index.html` to show the following information about you:
    * your name and class at WPI (e.g. class of 2025) Note: Do not put any contact or personal information that you do not potentially want other people outside of this class to see.
    * your major(s) and minor(s)
    * previous computer science courses that you have taken at WPI
    * your experience with the following technologies and methods (none, some, a lot)
        * HTML
        * CSS
        * JavaScript / Typescript
3. Complete some technical and/or design achievements (see below).
4. Test your project to make sure that when someone goes to your main page, it displays correctly. You can do this locally by simply running `node server.js` from within the assignment directory and then going to `localhost:3000` in your browser.
5. Modify the README file according to the specification below.
6. Commit and push all your changes to GitHub. 
7. Deploy your project to Render. You can do this by [importing the repo from GitHub](https://render.com/docs/github).
    * You will need to create an Render account first.
    * Under "Publish Directory", you can just put "./" (without the quotation marks).
8. Ensure that your project has the proper naming scheme (guide follows) so we can find it.
9. Create and submit a Pull Request to the original repo. This helps us find your project.
	* Ignore any messages about conflicts. You do not need to resolve them.
	* Make the title of your pull request "Pull Request for NAME" (ex. "Pull Request for Charlie Roberts")

### Note about alternative hosting
Our use of Render in this class is there as a convenience for you. However, if you are already familiar with hosting through other services--or if you would like to self-host--that's perfectly fine so long as the website in question meets all of the assignment requirements. Note that we will not be able to help you if you run into issues on other hosting platforms, and you will be responsible for making sure the website stays up and running for the duration of the term. For A1, you will also still need to create a pull request with your name and your website's URL.

Naming and URL Scheme
---

You must use a consistent naming scheme for all projects in this course.
If we can't find it, we can't grade it.

The name scheme should be `a1-yourFirstAndLastName`.
The `a1` will need to be updated to `a2`, `a3`, and so on in future assignments.

Rubric
---
For the Technical and Design achievements, make sure you thoroughly describe in your README what you did why it was challenging. ALL ACHIEVEMENTS MUST BE DESCRIBED IN YOUR README IN ORDER TO GET CREDIT FOR THEM. Remember that the success of Achievements hinges on how well you describe them in your README. Well formatted text, images, and concise and clear descriptions are helpful. You must include a Technical Achievements and Design Achievements section, even if none are attempted.

Note that if you want to load resources besides your index.html file (images, an CSS file, a JS file) you'll need to modify server.js to point to these. For now it's easiest to just hardcode paths to the resources, but we'll look at ways to optimize this shortly.

*Basic Requirements*

(10 points each)

1. Assignment has proper naming scheme
2. Files forked from original repo
3. `index.html` properly rendered
4. `index.html` page properly edited
5. All changes pushed to GitHub
6. Project deployed to Render (or other hosting option)
7. Pull Request submitted to original repo

*Technical Achievements*
1. (5 points) Style your page using CSS. Each style rule you apply will get you 1 point for a maximum of 5 points. Be sure to describe your style rules in your README.
2. (5 points) Add a simple JavaScript animation to the page.
3. (5 points) Experiment with other *semantic* HTML tags (links, images, tables, header, footer, etc.). Each extra tag you use will get you 1 point for a maximum of 5 points. Be sure to describe the tags you use in your README.

*Design Achievements*
1. (10 points) Create a color palette using [color.adobe.com](https://color.adobe.com). Use all the colors in the palette in your webpage by implementing the appropriate CSS. Add a small screenshot of the color wheel for your color palette to your repo.
2. (5 points) Use a font from [Google Fonts](https://fonts.google.com) in your website.

**NOTE:** There are additional color pallette and font options listed on Canvas under Modules -> Resources -> Color Pallettes and Fonts. You are welcome to use one of those instead. If you know of and would like to use any other resources that are not included, feel free to contact the instructor.

Sample Readme (delete the above when you're ready to submit, and modify the text below with your links and descriptions)
---

Rashi Roselin
http://a1-rashiroselin.onrender.com

This project shows an image of me and a brief description of my computer science experience at WPI.

## Technical Achievements
- **Styled page with CSS**: Added rules for the body (background color), p (text color and background color), title heading (font, font size, text color, and text alignment), second heading (text color and font size), table and th (solid border), and td (outset border).

- **Added JavaScript animation**: Added a simple animation of a green square moving across a blue background. Code inspired by https://www.w3schools.com/js/js_htmldom_animate.asp

- **Added semantic HTML tags**: Added header for the top, footer to house the animation, some sections to try to break up the page, an image of myself, an aside to house the image, a table of the classes I've taken, and an article section to house my experience with HTML, CSS, and JavaScript.

## Design Achievements
- **Used color pallette**: I used a complimentary red-green color pallette for my website.

- **Used the Handjet Font from Google Fonts**: I used Handjet as the font for the primary copy text in my site.
