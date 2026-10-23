ePortfolio - static HTML/CSS copy
================================

Open index.html in any browser. No installation or internet needed.

Files
-----
index.html                          Welcome page
engineering.html                    Engineering course (overview)
engineering-projects.html           Engineering course > Projects
mobility.html                       International Mobility (overview)
mobility-language-courses.html      International Mobility > Language courses
mobility-abroad.html                International Mobility > Mobility abroad
sustainability.html                 Sustainability & Civic Engagement
sport.html                          Sport & other activities
career.html                         Career Development (overview)
career-internships.html             Career Development > Internships
career-project.html                 Career Development > Career Project
cv-en.pdf / cv-fr.pdf               Your CVs (English / French), linked from the site
styles.css                          All styling (linked from every page)
favicon.ico                         Browser tab icon

Filling in your content
-----------------------
Every square bracket is a placeholder. Use Find & Replace in a text editor:
  [Your name]           -> your name
  [Your text here]      -> your own text
  [Your photo here]     -> <img src="photo.jpg" alt="Your name">
  [Your PDF here]       -> the file name of your CV (e.g. cv-en.pdf)
  [Your link here]      -> the full URL of your profile

To make a CV downloadable, replace the [Your PDF here] line with:
  <a href="cv-en.pdf">Download CV (PDF)</a>

To embed your elevator pitch video, replace the .video-slot block in
career-project.html with:
  <iframe src="https://www.youtube-nocookie.com/embed/VIDEO_ID"
          title="Elevator pitch" allowfullscreen
          style="aspect-ratio:16/7;width:100%;border:0"></iframe>

Notes
-----
- No analytics, no tracking cookies, no external fonts or scripts.
- The pages are a snapshot copy. If you change the live site, ask for a
  fresh export so this copy stays in sync.
