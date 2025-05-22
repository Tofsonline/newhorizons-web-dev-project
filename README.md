# Akinwunmi Jesutofunmi Diekoloreoluwa – Portfolio Project

This is my personal portfolio website, created as part of the Web Development Project organised by Bells University of Technology in collaboration with the New Horizons ICT Resource Centre. The goal was to simulate a real-world job interview with Tech-Genie International for the position of Senior Frontend Developer.

## My Process

First, I planned the structure of the site, creating sections such as 'Home', 'About', 'Projects', 'Skills', 'Experience', 'Contact' and 'Footer', all within a single HTML file. I wrote clean, semantic HTML5 and styled the layout using CSS3 with Flexbox and Grid for responsive design.

To make the site interactive and dynamic, I used JavaScript for:
- Responsive single-page layout
- Dynamic hero section
- Skills displayed with visual progress bars
- Interactive contact form with validation
- Footer with real-time date and time
- Clean, accessible design for all screen sizes

In the skills section, I added visual progress bars to represent my strengths. Each project was integrated from the 100 JavaScript Projects list (https://www.100jsprojects.com/projects), modified and styled to fit the theme of my portfolio.

Throughout the project, I organised my files into folders for CSS, JavaScript and images. I also used Git and GitHub for version control and hosted the site live using GitHub Pages.

## Features:

- Responsive single-page layout
- Dynamic hero section
- Skills displayed with visual progress bars
- Interactive contact form with validation
- Footer with real-time date and time
- Clean, accessible design for all screen sizes

## Technologies used:

- HTML5
- CSS3 (Flexbox and Grid)
- JavaScript (ES6)
- Git and GitHub

## Setup instructions

To run this project locally

1. *Clone this repository*: git clone https://github.com/Tofsonline/newhorizons-web-dev-project.git

2. *Navigate to the project folder*:
cd newhorizons-web-dev-project

3. *Open the project*:
Just open the index.html file in your favourite web browser.

No server or additional setup is required - it's a static frontend project.

Note: If you need to edit or customise this, use a code editor such as VS Code.


## Challenges & Solutions

1. *Bootstrap CDN conflict*
Challenge: When I added the Bootstrap CDN link in my HTML file, it affected the overall appearance of my site - including font sizes, colours and padding.
Solution: I fixed this by placing the Bootstrap CDN link above my custom CSS file in the <head> section of index.html. This allowed my styles to properly override Bootstrap's defaults.

2. *Background Image Not Showing After Deployment*
Challenge: After deploying my site to GitHub Pages, the background image for the hero section stopped displaying.
Solution: I discovered through online research that GitHub Pages requires more specific paths. So I changed the image URL from
background-image: url("../images/hero-section-image.jpg")
to:
background-image: url("/newhorizons-web-dev-project/project/images/hero-section-image.jpg");
And the image displayed correctly after that.

## Live demo:

https://tofsonline.github.io/newhorizons-web-dev-project/Project/

## Notes:

This project helped me to apply the skills that I gained during my training at New Horizons, and it made me feel more confident about building complete front-end solutions from scratch. It also prepared me for technical interviews by simulating real project workflows and portfolio presentations.

---

Thanks for checking out my work!
