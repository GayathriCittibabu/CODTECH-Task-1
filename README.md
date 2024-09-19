# CODTECH-Task-1

Name: C.GAYATHRI
Company: CODTECH IT SOLUTIONS
ID: CT12DS1911
Domain: Frontend Web Development
Duration: July to September 2024
Mentor: Neela Santhosh Kumar

Overview of the Project

The code represents a personal portfolio website for "Gayathri Cittibabu," showcasing skills, services, projects, and contact details. It's built using HTML for structure, CSS for styling, and JavaScript for interactivity. Here’s a breakdown of the key components:

HTML (Structure)
<html>: Defines the root of the HTML document.
<head>: Contains metadata like charset, viewport settings, and links to CSS files and external icons.
Meta tags define the character encoding, page description (for SEO), and viewport for mobile responsiveness.
Links to CSS files:
style.css: This is the external stylesheet that provides the visual styling.
font-awesome: Used for including icons, such as social media and navigation icons.
Header Section
<header>: Contains the website logo, navigation menu, and a hamburger icon (for mobile navigation).
<a href="#" class="logo">Portfolio</a>: Represents the portfolio title as a clickable logo.
Font Awesome icon (hamburger menu fa-bars) is used for toggling navigation in smaller screens.
<nav>: Contains navigation links like Home, About, Services, Portfolio, and Contact.
Home Section
<section id="home">: Contains a brief introduction to the developer.
Heading tags (<h3>, <h1>) introduce Gayathri and her role as a Frontend Developer.
<p>: Provides a personal bio.
Social Media Links: Each social media icon (LinkedIn, Behance, Instagram) uses Font Awesome icons for external links.
Download CV Button: <a href="Images/Gayathri resume.jpeg" download> allows users to download a resume.
About Section
<section id="about">: Describes Gayathri’s background and experience.
Contains an image and a description of her journey as a developer.
Read more button: Placeholder for additional information if needed.
Services Section
<section id="services">: Highlights the services offered, such as Web Development, UI/UX Design, and Graphic Design.
Each service has an icon (Font Awesome), title, description, and a button for more details.
Portfolio Section
<section id="portfolio">: Showcases recent projects with a screenshot and a short description.
Images are used to visually represent projects like a Calculator, Chat App, Text-to-Speech app, etc.
Hover effects (<div class="portfolio-layer">) reveal more information about each project.
Contact Section
<section id="contact">: Provides a contact form where users can input their details (name, email, message) and send a message.
Form includes text input fields and a submit button (<input type="submit" value="Send Message">).
Footer Section
<footer>: Includes copyright information and an "up" arrow button to scroll back to the top of the page.
CSS (Styling)
The CSS is referenced externally (style.css) and applies styling such as:

Layout styling: Responsible for positioning elements (header, sections, footer) and creating responsive behavior.
Typography: Defines fonts, colors, and sizes for text in headings and paragraphs.
Button styles: Styling for the buttons (e.g., "Download CV", "Read more").
Hover effects: For example, in the Portfolio section, when hovering over a project, a description is revealed.
Responsiveness: Media queries (if defined in the style.css file) adapt the layout for smaller screens.
JavaScript (Interactivity)
Two external scripts are referenced:

ScrollReveal (scrollreveal.min.js) is likely used for revealing elements on scroll to create smooth animations.
main.js: Custom JavaScript file (main.js) controls various interactive features such as:
Toggling the mobile navigation menu.
Scroll-based animations.
Dynamic interactivity like smooth scrolling or button clicks.
Key Functionalities
Navigation Menu: Links in the header allow users to scroll to various sections of the page.
Mobile-friendly: A hamburger icon appears on smaller screens for navigation.
Downloadable CV: Users can download a resume by clicking on the "Download CV" button.
Project Hover Effect: Hovering over projects in the portfolio reveals details about each one.
Contact Form: Users can submit their details through a form.
Final Remarks:
This portfolio page is well-structured to provide visitors with:

Information about Gayathri’s skills and services.
