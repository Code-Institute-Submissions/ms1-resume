# Dermot Keelan Resume

This is a resume site which provides information about me, my skills, my education and work experience, and my portfolio.
The site provides users with links to my social media (LinkedIn, Twitter and Instagram), and links at which a pdf version of my CV can be downloaded.
The site aims to provide users with any information they may need in considering my suitability for job vacancies or opportunities for collaboration.

The site is hosted on [GitHub Pages](https://dermot-k.github.io/ms1-resume/).

## UX

![](https://github.com/Dermot-K/ms1-resume/blob/master/assets/images/responsive-resume.png)



### User Stories

1. A recruitment agent seeking candidates for job vacancies and wants to learn more about me, and refer me to employers with job vacancies.
2. A recruitment agent wishes to contact me about job vacancies.
3. A potential employer wants to learn about my skills and experiences and obtain my CV.
4. A potential employer wants to contact me to discuss employment opportunities.
5. Potential collaborators seeking opportunities to work with others can assess my fit for their projects.

### Design

- The background image used across the site is from [Unsplash](https://unsplash.com/s/photos/workspace).
- The website uses the following colours for the header, footer and content containers
  - Grey #6f6f6f
  - Header and footer fonts: shades of lime green #a5d6a7 and #3ec878
  - Font color #f0f0f0

- Font families used are from [Google Fonts](https://fonts.google.com/).
  - Ubuntu for headings
  - Abel for paragraphs

### Wireframes
Wireframes were drawn up on [Figma](https://www.figma.com/file/FFWiW4o8IMre9ERQ2uoRGi/MS1-wireframe?node-id=14%3A8)

## Features

### Existing Features
- Bio info, my skills info, experience and portfolio
- Download links to PDF version of my CV
- Links to my social media accounts
- My contact information
- Documentation: ReadMe file
- Bootstrap CSS Framework
  - Grid layout: columns and rows
  - Content layout
- Responsive mobile first design
- Accessibility
- Git version control
- GitHub remote repository
- Deployed - hosted on GitHub Pages

### Planned Features
- JavaScript focused development
- Contact form

## Technologies Used
- [HTML](https://www.w3.org/html/)
  - HTML used for structure
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
  - CSS used for styling
- [Bootstrap](https://getbootstrap.com/docs/4.5/layout/overview/)
  - Bootstrap HTML/CSS framework used to structure and style page elements
- [Git](https://git-scm.com/)
  - Git version control
- [GitHub](https://github.com/)
  - Repository hosted on GitHub
- [GitPod](https://www.gitpod.io/)
  - Code for the project was written in the GitPod IDE
- [Google Chrome](https://www.google.com/chrome/)
  - Used for dev tools and browser
- [Microsoft Edge](https://www.microsoft.com/en-us/edge)
  - Used for dev tools and browser
- [Am I Responsive](http://ami.responsivedesign.is/#)
  - Used to test responsiveness of the site
- [Free Formatter](https://www.freeformatter.com/html-formatter.html#ad-output)
  - Used to format HTML in GitHub repository

## Testing

The site was manually tested on different devices and browsers to check responsiveness and functionality.

### Manual Testing
I reached out to some family and friends to test the site on their devices.
The site was tested on the following devices:
  - Samsung S10 - Viewport size 360px * 760px
  - Samsung S9+ - Viewport size 412px * 846px
  - Apple iPad - Viewport size 768px * 1024px

The site was found to be responsive and displaying as expected across the above screen sizes.

Issues uncovered:
1. Portfolio links were not opening in new tabs.
  - This was rectified by adding the correct target attribute to the html anchor tags.
2. A user reported difficulty reading the text in the experience page due to the container being transparent against the background image.
  - This was rectified by making the containers fully opaque.

### Testing on Different Browsers
I used Google Chrome and Microsoft Edge dev tools throughout the project.
The site functioned and responded as expected in both browsers when I tested them.

Issues uncovered:
1. A user reported an issue with the responsiveness in the iPad Pro viewport size (1024px * 1366px). The text on the index.html page was wrapping underneath my portrait image, rather than displaying side by side as intended.
  -  The Bootstrap columns were adjusted to create space on the row at this viewport size and margins were also amended. This rectified the issue.

### Code Validation
- HTML
  - All HTML was validated using the [W3C Markup Validation Service](https://validator.w3.org/).
  - Warnings were returned about consecutive hyphens used in comments. 

- CSS
  - The CSS file was validated using [Jigsaw](https://jigsaw.w3.org/css-validator/).
  - Errors and warnings relating to Bootstrap were returned. No issues with my custom CSS were highlighted.


### User Stories
1. A recruitment agent seeking candidates for job vacancies and wants to learn more about me, and refer me to employers with job vacancies.
  - On the homepage, skills page and experience page a user can obtain various information about me. The Download CV links in the header and footer can be used to obtain a CV which can be shared with potential employers.
2. A recruitment agent wishes to contact me about job vacancies.
  - On the home page the user can find my email address and phone number. The user can also scroll to the footer, click one of my social links and reach out to me there. The user can download my CV via links in the header and footer - my contact details are in that document.
3. A potential employer wants to learn about my skills and experiences and obtain my CV.
  - Clicking through to the skills, experiences and portfolio pages provides info. A downloadable CV can be accessed via the Download CV links in the header and footer.
4. A potential employer wants to contact me to discuss employment opportunities.
  - On the home page the user can find my email address and phone number. The user can also scroll to the footer, click one of my social links and reach out to me there. The user can download my CV via links in the header and footer - my contact details are in that document.
5. Potential collaborators seeking opportunities to work with others can assess my fit for their projects.
  - Collaborators can get info on my skills at the skills page and access my portfolio at the portfolio page.

## Deployment

The site is hosted on [GitHub Pages](https://dermot-k.github.io/ms1-resume/)

The process involved:

- Host a git repository on GitHub. Explained [here](https://help.github.com/en/github/getting-started-with-github/create-a-repo).
- The root folder contains README.md and index.html files
- On GitHub repository settings page move to GitHub Pages section
- Change source to master branch. (Or any desired branch)
- Provided link will be your projects home (index) page.

To deploy your own version of the website:

  - Have git installed
  - Visit the repository
  - Click 'Clone or download' and copy the code for http
  - Open your chosen IDE (Cloud9, VS Code, etc.)
  - Open a terminal in your root directory
  - Type 'git clone ' followed by the code taken from github repository
  - git clone https://github.com/Dermot-K/ms1-resume.git
  - When this completes you have your own version of the website
  - Feel free to make any changes to it
  - The website can be run by opening one of the HTML files within a web browser
  - Visit the link provided
  - Your website with any made changes will appear
  - Saved changes to the website will appear here after refreshing the page

The benefits of hosting your website on GitHub pages is that any pushed changes to your project will automatically update the website. Development branches can be created and merged to the master when complete.

It may take a moment for changes to appear on the hosted website.

## Credits
- Seun Owonikoko - for the guidance and mentoring I needed to get through my first project!
- Code Institute