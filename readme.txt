--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- 1/1 Readme
- */2 Basic HTML content
- */1 Basic CSS styling
- */1 Advanced feature
- */2 Responsive layout
- */1 Passes validation checks
- */2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features

    - Semantic HTML tags including <nav>, <footer>, <caption>, <thead>, and <tbody> for clear meanings
    - An image that shows my recent project that I presented, which includes proper alt text for the screen reader.
    - External links that go to my recent project, LinkedIn and GitHub
    - Appropriate headings and paragraph text: <h1><h2><h3> and <p> for bio paragraph.


(b) CSS features

    - Added custom fonts from google fonts with appropriate fallbacks: used 'Orbitron' (with 'Eurostile', 'Microgramma', 'Trebuchet MS', sans-serif fallbacks) for headings and 'Roboto Mono' (with 'Courier New', Courier, monospace fallbacks) for body and table text.
    - Used Bootstraps CSS including containers (.container), grid layout classes (.row, .col-12, .col-md-6, .col-10, .col-2), navbar helpers (.navbar), and responsive image scaling (.img-fluid).
    - Modified padding and margins for better readability: custom top padding across media queries (.img-paragraph), and flexbox spacing (justify-content: space-between, align-items: center).

(c) Advanced features

    - Created a table with multiple columns and rows that could be read with a screen reader: 3-column, 4-row. Used semantic <thead>, <tbody>, <th scope="col">, and a visually hidden <caption> (1px width/height with overflow: hidden) to help assistive technologies
    - Created more complex page layout that has navigation bar and responsive multi-breakpoint adjustments


3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.

    I got 0 Known Problems and 0 Likely Problems on AChecker. I ended up ignoring the 28 "Potential Problems, since most of them are not really required to make this website accessible: 

    1. Image and alt text checks: Achecker asks if the image I used is decorative, requires long description, or contains uncaptured text/poor contrast. However the photo is meaningful content and I believe my alt text ("Lien standing next to his team's bituin project presentation poster.") clearly shows the purpose of the image, without needing long descriptions. 

    2. Table Structure Checks: Achecker asks if my table layout is missing the <th> tags, <caption> idetifies table well, etc. However since my table is a true data table, not a layout table. Additionally, I believe my <caption> ("Overview of skills and technologies") explcitly identifies its purpose.

    3.  Headings, page title, link checks: Achecker asks if my tags such as <h> and <a>, are meaningful not just because. I believe all my html tags represent meaningful placements because they correspond to their purpose. Ex: <a> tag will actually take user to a related link. 

    4. etc: Checks such as multi-page checks on <body>. These are the other picky checks such as potential for missing site maps. Since my portfolio is a concise, single-page english site, these complexity checks do not really pose and dangers. 

4. How long, in hours, did it take you to complete this assignment?

    According to github commits and including the time it takes to learn new information while doing the project, I would say about 9-12 hours. 

5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)

    https://www.w3schools.com/cssref/index.php
    https://css-tricks.com/snippets/css/a-guide-to-flexbox/
    https://www.figma.com/resource-library/best-fonts-for-websites/
    https://www.w3schools.com/css/css_boxmodel.asp
    https://www.w3schools.com/cssref/css_websafe_fonts.php
    https://www.w3schools.com/css/css_overflow.asp
    https://www.w3schools.com/tags/att_scope.asp
    https://www.w3schools.com/tags/tag_caption.asp
    Google Fonts (Orbitron and Roboto Mono): https://fonts.google.com/
    Generative AI (Google Gemini) to help explain concepts such as boxmodel, flexbox, etc. 

6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?



7. Is there anything special we need to know in order to run your code?

