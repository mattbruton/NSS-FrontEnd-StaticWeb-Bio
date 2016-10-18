# HTML Exercise - Bio

This is an introductory NSS Evening Cohort 3 exercise that focuses on semantic HTML and includes a minimal amount of basic CSS. Introduced the concept of linking multiple html files together and creating navigation to switch between pages.

==============================

- Viewing/Downloading Project
    - [To View Hosted Project](#to-view-hosted-project)
    - [Installation](#installation)
    - [To Run](#torun)
- Specifications and Project Information
    - [Languages] (#languages)
    - [Tools] (#tools)
    - [Specifications] (#specifications)

## Viewing/Downloading Project

### To View Hosted Project

[HTML Exercise - Bio](https://mb-nss-exercises.firebaseapp.com/bio/index.html)

### Installation

Clone the repository from GitHub:

`git clone https://github.com/mattbruton/NSS-FrontEnd-StaticWeb-Bio.git`

Navigate to the project from the directory it was cloned into:

`cd NSS-FrontEnd-StaticWeb-Bio/`

### To Run

If you need a command line http server, to install http-server globally:

`npm install http-server -g`

Then:

`http-server` or `http-server -p XXXX` (the X's represent the port of your choice)

You should now be able to open your browser and type `localhost:8080` to view the project.

## Specs and Project Information

### Languages

1. HTML
1. CSS

### Tools Used

1. [Git](https://git-scm.com/)
1. [Atom](https://atom.io/)
1. [NPM http-server](https://www.npmjs.com/package/http-server)

### Specifications

Create a two page site for your own personal branding. This is an HTML exercises, so while you may style this site to your heart's content, we will be focusing on the HTML structure and syntax of your code.

### Pages

#### Professional history page

Basically an HTML version of your resume.

1. Each place you've worked must be contained in an article element.
1. Each article element should have a header that contains the name of the company and the dates of your employment. Ensure that the dates are semantically marked by being contained within the appropriate HTML element.
1. Each article should contain at least one section that describes your position there.
1. No footer required for these articles.

#### Contact information page.

1. One article.
1. A heading (e.g. "How to contact me").
1. Four sections that contain a home address, a phone number, and two social media URLs.

### Common page elements

#### Navigation

Create a navigation bar on each page that contains a link to both pages. You can use whatever elements you like for the navigation, but it must be contained in the appropriate HTML5 semantic element.

#### Page header

Each page should have an `<h1>` title contained in the appropriate HTML5 semantic tag.

#### Page footer

Each page should have the same footer information. Put whatever information you like in the footer.