
CSS font-size resources:
CSS units for font-size: px | em | rem (https://medium.com/code-better/css-units-for-font-size-px-em-rem-79f7e592bb97)

A third view (https://css-tricks.com/rems-ems/) comes from Chris Coyier of CSS-Tricks. His solution makes use of all three units we encountered so far. He keeps the root size defined in px, modules defined with rem units, and elements inside modules sized with em.
So here’s my idea: you still keep px size adjustments at the document level so you can make easy/efficient sweeping size changes. But then each module on the page has a font-size set in rem. Actual text elements (h1, h2, p, li, whatever), if you size them at all, are sized in em, and thus become relative to the module.

Problem Statement
Your company has recently started on a project that aims to conduct a survey to measure the demands and interests of its customers. So you and your colleagues have started to work on the project.
Project Design
FIGMA Design(https://www.figma.com/file/HXULRJVkPlaCpxQlbm82bX/Project001?node-id=6%3A4)

Objective
Build a Survey Form that is functionally similar to this: Survey Form (https://mccarthy-silva.github.io/Survey-Form/)
At the end of the project, following topics are to be covered;
HTML Forms-Input Types
HTML Form Elements
CSS Colors-Border Properties
CSS Margins-Padding
CSS Properties for Texts-Font Families-Links
At the end of the project, students will be able to;
improve coding skills within HTML & CSS
use git commands (push, pull, commit, add etc.) and Github as Version Control System.

Part-1 HTML Structure
- Creat structure of the HTML5
- Give name of your project (title)
- Create the main structure of the container (div id="container")
- Create Main Topic of the project (id="title")
- Create a description of your project (id="description")
- Create a form (id="survey-form")
- Create 4 divisions (class="box") for each label and single-line text
input field (Tips:Don't forget to use placeholder)
- Create a division (class="box") for a dropdown list. (Tips:dont forget to
use a label tag)
- Create a division (class="box") for checkbox list
- Create a division (class="box") for radio buttons
- Create a division (class="box") for a multi-line input field (Tips: a
text area)
- Create a button for id="submit" the form

Part-2 CSS Structure
Set a background and define font-color="white"
- Set container background color and margin
- Define "title" and "description" color-size-padding etc...
- Define "survey-form" color-size-padding etc..
- Define labels color-size-padding etc... (Tips: id="name", "email",
"number" ...)
- Set class color-size-padding-margin etc...
- Define id="submit" color-size-padding etc...
Step 4: Push your application into your own public repo on Github
Step 5: Deploy your application on Github template to showcase your app within your team.