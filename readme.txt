--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
- A headshot on the home page with alt text
- Headings and paragraphs on every page, going in order from h1 to h2 to h3
- Links to my LinkedIn, GitHub, and email
- Four pages (Home, Projects, Experience, Contact) connected by the same nav bar
- Semantic tags like header, nav, main, section, article, aside, and footer
- Font Awesome icons on the home page, in the footer, and on the contact page


(b) CSS features
- Custom padding and margins on each section so the content has room to breathe
- My own color palette (cream, baby pink, mauve, and brown) used for backgrounds, buttons, links, and borders. I kept the text dark brown so it'll still easy to read.
- Bootstrap's grid, navbar, buttons, form styles, and responsive table
- Two Google Fonts: Cormorant Garamond for headings and DM Sans for body text, with Georgia/serid and Helvetica/Arial/sans-serif as fallbacks


(c) Advanced features
- A nav bar that turns into a menu button on smaller screens
- A table on the Experience page with a caption and column headers (scope="col") so screen readers can read it
- A contact form with a label for every field and required fields
- A timeline on the Experience page made with CSS grid, which switches to one column on phones
- The site is also live on GitHub Pages: https://viviannezhou.github.io/a1-portfolio/ 

For responsiveness: on phoens my photo moves above the intro and gets small, the boxes and project cards stack into one column, the timeline dates move above each job, and the headings and spacing shrink so nothing feels crowded.


3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

All four pages have 0 Known Problems in AChecker. To get there, I switched my Font Awesome icons from <i> tags to <span> tags, and I changed the Experience table to only use column headers.

The Experience page has 1 Likely Problem (Check 82, "p element may be misused, could be a header") for "University of California, Irvine" being in bold. I left it because it isn't acting as a heading. That section already has a real heading ("Education") right above it, and the bold text is just the school name inside it, so the page structure still makes sense for screen readers.

Each page also has around 35 to 43 Potential Problems. These are things AChecker wants a person to double check, like whether link text is clear, whether there's enough color contrast, and whether the reading order makes sense. I went through them and they're fine: my links say where they go, my text is dark brown or deep mauve on cream or white backgrounds so the contrast is strong, and the icons are marked aria-hidden="true" since the words next to them already explain what they are.


4. How long, in hours, did it take you to complete this assignment?

About 7 hours


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

- https://getbootstrap.com/docs/5.3/ (grid, navbar, forms, tables)
- https://fonts.google.com/ (Cormorant Garamond and DM Sans)
- https://fontawesome.com/icons
- https://validator.w3.org/ and https://jigsaw.w3.org/css-validator/
- https://achecker.achecks.ca/
- https://docs.github.com/en/pages (to put the site online)
- Claude (Anthropic): I used Claude as a guide while building the site. It walked me through each section step by step and gave me starting HTML and CSS code, which I then customized with my own content, color palette, fonts, photo, and layout changes. I also used it to explain Bootstrap and CSS concepts I wasn't familiar with, help me set up Git and GitHub Pages, and figure out how to fix the errors the HTML and accessibility checkers found.

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

None


7. Is there anything special we need to know in order to run your code?

No special setup needed. Open index.html in any browser (with internet, since Bootstrap, Font Awesome, and the fonts load online). The site is also live at https://viviannezhou.github.io/a1-portfolio/. All four pages share one stylesheet, so the CSS validation screenshots are the same for each page.
