<<<<<<< HEAD
# Job Application Form 

This is my first project built from scratch. A job application form based on clean minimalist code.

## AIM 

 The goal of this project is to move beyond the basic *HTML* and create clean distraction-free  interface   that mimics a real-world hiring tool.

 ## FEATURES 
* *Responsive design*: Utilized max width and percentage width so that the form is accessible on both 
   mobile devices and desktops. In this case i set max-width to `500px` (for desktop) and width: `80%` for
   (mobile devices).

*  *Accesibility*: *Semantic HTML5* for accesibility. Elements like fieldset and input elements.

*  *Custom Styling*: Use of *CSS3* to make the form visually appealing, styled the button and the form's 
    background color.

*  *Form Validation*: Uses *HTML5* required attribute to ensure the user inputs valid information.

 ## Technical Stack 

 * *HTML5*
 * *CSS3*

## Challenges & Solutions 

* I struggled a good one with the invalid and valid pseudo class. When i set the input and textarea 
  elements to turn red when invalid, it technically meant the browser would 'shout' at the user even 
  before typing anything because of how the browser perceives it. So what did i do? Optimized the 
  user-invalid element instead. I debugged and learnt something new.

* The select element:Come to this part, the user is supposed to select a job position. The problem was 
  the first option that  was the cue to show the user what to do, became an option by default alongside 
  other options. To solve this i set it to `(option value=" " selected disabled)`. This way the user could
  not choose it even by mistake.

* Error 404 & Repository Structure- I then came to face another bug, Error 404 for the first time in my
  code years. What i had not initially realized was that my project was buried in a sub-folder and the 
  main file was not named *index.html*. I solved this by restructuring my local folders, renaming the
  file to index.html ensuring it was the root directory for GitHub Pages to find it.

##  Live Demo 

 [Click here to view the live form](https://annndegwa.github.io/job-application-form/)

=======
# HTML & CSS Foundations ⚒️

I started my self-study journey in February 2026. This repository is a collection of projects and exercises I’ve built while working through the **freeCodeCamp** curriculum. My goal is to master the core building blocks of the web with a clean, problem solving approach.

## 📁 Project Highlights

**dev-hub.html**
A professional developer profile card. I focused on **accessibility** and responsive scaling by using `rem` and `percentages` to ensure the layout works across all screen sizes.

**event-flyer.html**
A project where I practiced creating a visual layout using only HTML and CSS. It helped me understand how to structure content for a specific theme while keeping the code semantic.

**movie-review.html & blog-card.html**
Practice files focusing on **Semantic HTML**. I used tags like `<article>`, `<section>`, and `<header>` to make the code meaningful for browsers and screen readers.

## 🛠️ Technical Progress (Since Feb)
- **HTML Mastery:** Completed nearly 300 steps covering semantic structure, complex forms, and data tables.
- **CSS Architecture:** Finished 140+ steps focusing on the Box Model, typography, and relative units.
-It has been worth the struggle!!
- **The "Path" Struggle:** One of my biggest learning curves was mastering **absolute and relative paths**. I spent time troubleshooting how to correctly use px, rems, ems , vw, and vh. With consistency 
   being king, i eventually got the hang of things.
- **Interactivity:** Currently learning **Pseudo-classes** to handle user states like `:hover` and `:focus`.

## My 2026 Goals
- Finish the freeCodeCamp certification to get the basics out of the way.
- Getting my **Front-End** layouts to actually work and look professional on a phone.
- Get to a point where I don't get stuck on small things like linking images and CSS files.
- Keep my code and my workspace working and clean
>>>>>>> 5937b05f042a6b19851cd708d018bdb8ef32cbd1
