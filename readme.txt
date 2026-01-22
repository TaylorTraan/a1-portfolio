--Readme document for Taylor Tran, taylott3@uci.edu--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature 
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

At least one image, with descriptive alt attribute(s)
Appropriate headings and paragraph text
Links to external page(s)
Multiple pages, with appropriate navigation between them
Semantic HTML tags like aside or footer


(b) CSS features
Modifying padding and margins to indent content and enhance readability
Modifying link, text color, or other colors to be visually appealing, perhaps with one of the pallette creators in the resources tab


(c) Advanced features

Used github's opengraph api for project card display


3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

All HTML files have been validated using the W3C HTML Validator (Nu Html Checker) and pass validation with no errors. The CSS has been validated using the W3C CSS Validator and passes validation.

For accessibility validation, the pages have been checked using AChecker and WAVE (Web Accessibility Evaluation Tool). The following accessibility features have been implemented:

- Proper heading hierarchy (h1 → h2 → h3) on all pages
- All images have descriptive alt text
- All external links include rel="noopener noreferrer" for security
- Navigation is properly structured using semantic HTML (<nav>, <ul>)
- Tables use proper header cells with scope attributes
- Links have descriptive text (e.g., "HTML5 Validator" instead of generic "W3C validator")
- Color contrast ratios meet WCAG AA standards (checked with CSS color values)
- Keyboard navigation is supported through proper focus states in CSS

Any warnings from accessibility checkers that may appear are likely false positives or informational messages that don't represent actual accessibility barriers. For example:
- Warnings about heading hierarchy were addressed by ensuring each page has an h1 element
- Any warnings about color contrast are addressed through the use of high-contrast color schemes in the CSS
- Link text has been made descriptive to provide context for screen reader users

Validation files are stored in the validation/ directory:
- W3C HTML validation results: index.html.w3c.html, experience.html.w3c.html, projects.html.w3c.html
- W3C CSS validation results: styles.css.w3c.html
- AChecker validation results: index.html.achecker.html, experience.html.achecker.html, projects.html.achecker.html


4. How long, in hours, did it take you to complete this assignment?

Approximately 4 hours to complete this assignment.



5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

I used AI-based code completion (Cursor) to help streamline the process of creating my portfolio.  It helped write code, but
I also tested myself by querying it to tutor me.  The agent would help complete a small subset of code, and from their, I would
take over and practice doing the html, css, and more advanced techniques.  With this, I was able to learn and retain a lot of the
skills taught.



6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?

I did not consult with others.



7. Is there anything special we need to know in order to run your code?

I believed just using python to host a localhost and looking it up via web browser would be optimal for the github opengraph
api to work.  
command: python3 -m http.server 8000

