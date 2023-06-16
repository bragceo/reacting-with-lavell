# Reacting With Lavell

## Description 

Reacting With Lavell is a single-page application (SPA) built with React.js, which will serve as my portfolio website to show case some of my projects as a developer. The website showcases my bio, work samples, contact information, and resume. It uses React Router to facilitate navigation between different sections without reloading the page.


## User Story

AS AN employer looking for candidates with experience building single-page applications <br>
I WANT to view a potential employee's deployed React portfolio of work samples <br>
SO THAT I can assess whether they're a good candidate for an open position <br>

## Acceptance Criteria

GIVEN a single-page application portfolio for a web developer <br>
WHEN I load the portfolio <br>
THEN I am presented with a page containing a header, a section for content, and a footer <br>
WHEN I view the header <br>
THEN I am presented with the developer's name and navigation with titles corresponding to different sections of the portfolio <br>
WHEN I view the navigation titles <br>
THEN I am presented with the titles About Me, Portfolio, Contact, and Resume, and the title corresponding to the current section is highlighted <br>
WHEN I click on a navigation title <br>
THEN I am presented with the corresponding section below the navigation without the page reloading and that title is highlighted <br>
WHEN I load the portfolio the first time <br>
THEN the About Me title and section are selected by default <br>
WHEN I am presented with the About Me section <br>
THEN I see a recent photo or avatar of the developer and a short bio about them <br>
WHEN I am presented with the Portfolio section <br>
THEN I see titled images of six of the developer’s applications with links to both the deployed applications and the corresponding GitHub repository <br>
WHEN I am presented with the Contact section <br>
THEN I see a contact form with fields for a name, an email address, and a message <br>
WHEN I move my cursor out of one of the form fields without entering text <br>
THEN I receive a notification that this field is required <br>
WHEN I enter text into the email address field <br>
THEN I receive a notification if I have entered an invalid email address <br>
WHEN I am presented with the Resume section <br>
THEN I see a link to a downloadable resume and a list of the developer’s proficiencies <br>
WHEN I view the footer <br>
THEN I am presented with text or icon links to the developer’s GitHub and LinkedIn profiles <br>


## Deployed URL

https://bragceo.github.io/reacting-with-lavell/

## Github Repository

https://github.com/bragceo/reacting-with-lavell

## Overview of Code structure and its components:

Here is a detailed overview of each file (note: Developer = me, Lavell Juan):

App.js: This is the main entry point of the application. It uses React Router to define the routes for different sections of the application: About, Projects, Contact, and Resume. Each of these sections are components rendered based on the current route. The Header and Footer components are displayed on all routes.

Header.js and Navigation.js: These components display the header of the website, which includes the developer's name and navigation links to different sections of the portfolio. Navigation is handled by React Router's NavLink component, which automatically adds an 'active' class to the link corresponding to the current route.

About.js: This component displays a brief biography and a photo of the developer. The bio describes my career background and achievements.

Projects.js and Project.js: The Projects component maps over the projectsData. Each Project component displays a project's image, name, and technology stack, and also provides links to the deployed application and its GitHub repository.

Contact.js: This component displays the developer's contact information and a contact form. The form includes validation logic to check for required fields and a valid email address. Validation messages are managed via state hooks and are displayed to the user when necessary.

Resume.js: This component displays a link to the developer's resume and lists their front-end and back-end proficiencies.

Footer.js: This component displays links to the developer's LinkedIn, GitHub, and Twitter profiles.
 

## How to run the application
 
Running the application locally:

Running the application locally will require Node.js and npm (Node Package Manager) to be installed on your system.

Once that is done, clone or download the Repository and in the root directory of the Repository install dependencies (i.e., npm install).

Note: If the application uses environment variables (like in the server.js file for the PORT), you will need to set these up. This can be done by creating a .env file in the root of your project and specifying the variables there, like PORT=3000. 

Once everything is set up, you can start the application by running an npm start in the command line.

Lastly open a web browser and visit http://localhost:<PORT> (note: replace <PORT> with the port number your server is running on, e.g., http://localhost:3000). You should see your application running.



## Special Thanks 

Shout out to the awesome Instructors and TAs who worked with me through numerous challenges. These individuals include: Diego, Enrique Gomes, and Erik Hoverstein. 



## Authors 

Lavell Juan <br>



## Credits 

N/a

## License 

Please refer to license in repo 

