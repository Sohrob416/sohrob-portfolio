# Sohrob Niazi - Personal Portfolio

## Current status
First draft. Four pages and responsive CSS are present. This draft is NOT ready for submission: the video is 44.2 seconds and must be replaced with a 45-60 second take; official validation and GitHub publishing remain outstanding.

## Pages
- index.html: introduction and navigation.
- about.html: education, work and interests. Own photo and introduction video included; current video needs a slightly longer replacement.
- projects.html: four school projects supplied by Sohrob.
- contact.html: name, email, cell number, comments, submit and reset.

## Lecture sources and authorship
Adapted lecture patterns provided by course instructor Ahmed Sheikh for INFR3120:
- Week1(1).zip / index.html and index.css: wrapper, navigation links, fonts, colours, margins, padding, gradients, borders and hover styles.
- Week2.zip / videos.html: the video controls, source and poster pattern to use when personal media is supplied.
- Week3 Code.zip / semantic.html: header, nav, article, section, footer and email links.
- Week3 Code.zip / form.html: labels, fields, required, email input, textarea, submit/reset and mailto submission.
- Week3 Code.zip / responsive.html, fluid.css, tablet.css and smartphone.css: viewport metadata, percentage widths and separate viewport stylesheets.
- Week-4.pdf: display:inline-block and line-height.

The page content and styles adapt these patterns to this portfolio. Lecture examples contain mistakes; this project corrects label associations and document structure rather than copying those mistakes.

## Addition requiring confirmation
The assignment requires phone validation. The supplied form examples do not demonstrate type="tel", pattern or title. The phone field uses pattern="[0-9]{10}" to accept exactly ten digits; [0-9] means a digit and {10} means ten occurrences. This addition is explicitly identified in the HTML. Confirm it is within the permitted course material before final submission. Email validation and required fields follow the class examples.

## Responsive design
- Mobile: up to 480px. A 96% wrapper, stacked navigation and smaller padding preserve space.
- Tablet: 481-959px. A 94% wrapper and navigation across the top.
- Laptop: 960px and above. An 88% wrapper with a floated left header and right content column. The footer uses clear:both, following the lecture pattern.
The breakpoints match Week 3. Percentage widths make the layout fluid. No Flexbox, Grid, framework or JavaScript is used.

## Style and colour scheme
A warm cream background, burgundy navigation and olive borders give the website a simple paper-like appearance. Georgia is the main font, using the same font-family property taught in class. Projects are divided with borders instead of rounded cards.
Colours: #F7F1E5 (cream), #E8DFC9 (sand), #542B35 (burgundy), #773F43 (muted red), #756D52 (olive), #302B25 (dark brown).
The palette still needs documenting in Adobe Color for the assignment.

## Gradients
- style.css body: vertical linear gradient from #DED3BA to #F7F1E5.
- style.css header: 135-degree angle linear gradient from #542B35 to #773F43.

## Form behaviour
The mailto form follows the lecture and opens the visitor's configured email app after browser validation. It does not automatically deliver a message or store submissions. Test with a configured email app.

## Remaining work and validation
- Replace the current 44.2 second video with a 45-60 second recording. Controls and a poster image are included.
- Confirm phone validation syntax and Adobe Color scheme requirement.
- Validate all four HTML files with W3C Markup Validation Service.
- Validate all CSS with W3C CSS Validation Service.
- Run W3C Link Checker on the deployed website.
- Spell-check and test all pages with WAVE.
- Inspect mobile, tablet and laptop layouts and test invalid/valid form inputs.
- Create a public GitHub repository. Commit real development stages as they happen; do not invent earlier history.
- Publish with GitHub Pages and add the live site and repository links here.
- Submit the final ZIP, live site link and repository link on Canvas.

Official validator and WAVE checks have NOT yet been performed. Local link and structural checks are not substitutes.

## Media
The photo and video were supplied by Sohrob. The video poster is a frame from his recording.

## Open locally
Extract the ZIP and open index.html in a browser. Keep all pages and the css folder together.
