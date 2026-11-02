<div align="center">
Amlan Shanker · Portfolio

A cinematic, Dune-inspired portfolio for a full stack developer. Desert dunes, drifting sand, a flying ornithopter, and an interactive page that reacts to your cursor and your scroll.

Live site

HTML5 CSS3 JavaScript GitHub Pages

View the live site →

</div>
About

This is my personal portfolio website. It introduces who I am, shows the projects I've built, lists the technologies I work with, and links to where you can reach me.

The whole site is one static page with no framework and no build step. It's styled as a quiet, widescreen scene on Arrakis: a hazy sun over layered sand dunes, with details that reward exploring.

Sections
Section	What's in it
Hero	My name, role, availability, and calls to action over an animated desert scene
About	A short story of what I build and what I'm focusing on now
Projects	Six projects, each linking to its GitHub repository
Stack	Frontend, backend, database, mobile, and tools
Contact	Links to GitHub, LinkedIn, LeetCode, and Spotify
Projects featured
Project	Description	Stack
GenZenius	AI-powered SaaS platform: article generation, blog title suggestions, image generation, background removal, object removal, and resume tools	JavaScript, AI
Finance Dashboard	Finance dashboard built with MongoDB, Express, React, and Node.js	MERN
Expense Tracker	Expense tracker for logging and reviewing spending	MERN
Social Media App	Dynamic social media application	MERN
Notes App	Android notes app built in Android Studio	Kotlin, XML
Movie Ticket Booking	Responsive web app to register, log in, browse movies, calculate ticket costs, and book tickets	HTML
Features
Cinematic scene
Film-style intro: a black screen with my name, then the screen opens like a curtain
Layered sand dunes with a monolith and a tiny lone figure on the ridges
A hazy sun with a lens-flare streak, twinkling stars, two drifting moons, and shooting stars
An ornithopter with flapping wings that crosses the sky
Wind-blown sand and drifting dust, with a slow camera push-in on the dunes
Thin widescreen bars and a subtle film-grain overlay
Interactivity
Parallax: the dune layers shift with the mouse (or touch drag) and at different speeds as you scroll
Letters that react: the letters of my name lift and glow as the cursor approaches
Sandstorm: click and hold in the hero and the sand rushes faster
Custom cursor: a smooth ring and dot, a trail of sand grains, ripples on click, and an "OPEN" label over project rows
Magnetic buttons that lean toward the cursor
Tilt cards that follow the cursor in 3D, and spotlight hover effects on project rows
Scroll and motion
Reveal-on-scroll with blur, slide, and stagger, with project rows alternating from left and right
Headings that scramble through random letters and settle on the real word
Words in the About text that light up as you read
A scroll-speed skew on the project list and stack columns
A scroll progress bar, an active-section indicator, and a back-to-top button
Two scrolling tech marquees, one in each direction
Quality
Responsive: phones, tablets, laptops, large screens, and short landscape screens
Light and dark themes with a toggle (follows the system setting by default)
Accessible: keyboard focus styles, semantic landmarks, and prefers-reduced-motion support that turns animations off
Touch-friendly: cursor effects only appear on devices with a mouse
Tech stack
HTML5, CSS3 (custom properties, grid, flexbox, keyframe animations), and vanilla JavaScript
Canvas 2D for the wind-blown sand and inline SVG for the dunes, monolith, figure, and ornithopter
Google Fonts: Marcellus (headings) and Inter (body)
No frameworks, no bundler, no dependencies
Project structure
Portfolio/
├── index.html      # the entire site: markup, styles, and scripts
└── README.md
Run it locally

No install needed.

bash
git clone https://github.com/AmlanShanker/Portfolio.git
cd Portfolio

Then open index.html in your browser. For a local server instead:

bash
python -m http.server 8000
# open http://localhost:8000
Customize

Everything lives in index.html:

To change	Look for
Colors and themes	The :root variables at the top of the <style> block
Name, role, and tagline	The .title block inside the <header class="hero">
About text	<section class="s" id="about">
Projects	The .row links inside <section ... id="work">
Stack	The .cast columns inside <section ... id="stack">
Contact links	The .cta buttons inside <section class="end" id="contact">
Tech marquee words	The <span> items in #mt
Deployment

The site is hosted on GitHub Pages:

Push index.html to the repository's main branch.
Open Settings → Pages.
Under Build and deployment, choose Deploy from a branch, then select main and / (root).
Save. The site goes live at https://amlanshanker.github.io/Portfolio/.
Browser support

Works in current versions of Chrome, Edge, Firefox, and Safari. Older browsers fall back gracefully: content stays readable without the animations.

Credits
Visual mood inspired by the film Dune. This is a fan-style tribute; no film assets are used, and everything is drawn in code.
Fonts: Marcellus and Inter, via Google Fonts.
Contact
GitHub: @AmlanShanker
LinkedIn: amlan-shanker
LeetCode: tiPha4TJ2s
Spotify: profile
<div align="center">

Learn · Build · Improve · Ship

</div>
