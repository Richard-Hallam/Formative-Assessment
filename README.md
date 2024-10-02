# Formative Assessment - Mental Health Awareness

## Overview

### Purpose
The purpose of this project is to communicate the importance of mental health and raise awareness of it. This will be achieved by clearly displaying information on the subject and by linking to more in depth resources in an easy to use way.

### Target Audience
The target audience is anyone with an interest in learning about mental health.

## User Stories

### Must-Have User Stories
- **As a user I want to be able to navigate the website easily:**   
--  **Acceptance Criteria:** The website has a clear navigation menu allowing all pages to be accessed easily
-  **As a user I want to be able to follow links to other pages**
--  **Acceptance Criteria:** All pages will be linked to each other with links that are clear to the user.
-  **As a user I want to be able to interact with the website without any issues.**
--  **Acceptance Criteria:** There will be no errors, missing content or broken links.
-  **As a visually impaired user I want the website to work well with my screen reader.**
--  **Acceptance Criteria:** The website will contain accessabilty tags throughout enabling screen readers to work well with it.


### Should-Have User Stories
- **As a user I want the site to work on both mobile and desktop:**  
--  **Acceptance Criteria:** The site will be responsive to changes in screen size and adapt to smaller phones screens as well as larger desktop monitors. All content should still display correctly regardless of device used.
- **As a user I want to have the content in an easy to read format:**   
--  **Acceptance Criteria:** The content will be in an easy to read font and displayed at an apropriate size for the screen it is viewed on. All links and other interactive elements are identified to the screen reader


### Could-Have User Stories
- **As a user when I mouse over an element it reacts to being hovered over.:**   
--  **Acceptance Criteria:** Elements where it is sensible to do so react to being hovered over with the mouse
- **As a site user I can load the page quickly:**   
--  **Acceptance Criteria:** Pictures will be optimised for the web and efforts made to ensure fast loading of the webpage


## Design Decisions

### Colour Palette
![Image of the colour palette chosen for this project](assets/Wireframes/ColourPalette.png)
These colours were chosen to provide a calming theme for the project while maintaining stylistic consistency.

### Wireframes
Include wireframes for key sections of your website.  
Briefly describe the design choices, including layout, colour schemes, and fonts.  
**Guidance:** Start this section during Phase 1: Ideation & Initial Setup and update it throughout Phase 2 and Phase 3. Include digital wireframes created in Phase 1. Document the reasoning behind your layout choices, colour schemes, and font selections.
**Homepage mobile layout**
![Mobile Wireframe image](assets/Wireframes/mobileWireframe.png)
This is the layout for mobile. In this version the menu is hidden and makes use of a burger button for a clean look.
**About Desktop layout**
![Desktop wireframe Image](assets/Wireframes/DesktopWireframeAbout.png)
This is the layout for desktop. Making use of the extra space to hide the burger button and instead showing the menu at all times. The menu will always be visible. The content is laid out in containers with the text containers being twice as large as the images and the images with padding taking up a third of the page.

### Typography
**Font**
https://fonts.google.com/share?selection.family=Lexend+Deca:wght@100..900
This font was chosen for both the main body text because it looks neat and is was designed for people with dyslexia and other reading problems in mind. This has the added benefit of increasing accessability. The fallback font is sans-serif. 

### Accessibility Considerations
Attributes for screen readers were included throughout the project. Font choice as explained in the above section was also decided based on accessibility.

## Features Implementation

### Core Features (Must-Haves)
- **Easy to navigate:** The website is a single page application with a fix menu that allows quick navigation to the different sections of the site.
- **Links take the user to other pages** All links have been tested and open the correct external resource in a new tab
- **No issues with the website** The website was checked for readability on multiple screen sizes and run through a html and css validator to check for errors.
- **Is accessible for visually impaired users** All images have descriptive alt attributes and the nav bar has the correct aria tags for screen readers.

### Advanced Features (Should-Haves)
- **The site is usable on both mobile and desktop:**Testing of both mobile and desktop screen sizes was conducted using chrome dev tools.
- **Content is easy to read:** A contrasting font colour was chosen and the font family was selected with readability in mind.
(Include all should-have features)  

### Optional Features (Could-Haves)
- **Elements react when moused over:** Not implimented would be distracting on elements other than possibly the external links.
- **The page loads quickly:** Images were selected with fast loading in mind. 

(Include any could-have features that were implemented or considered)  
**Guidance:** If any could-have features were implemented, describe them here. This is an opportunity to showcase extra work done beyond the initial scope. But remember - keep it simple! Focus on the Must stories first. Could user story features are commonly earmarked for future project iterations.


## Testing and Validation

### Testing Results
Testing layout on various screen sizes was done using chrome dev tools. Testing of loading speed was done on a slow 3g network using my mobile phone in a chromium based mobile browser.

### Validation
**CSS validation**
![image of css validation](/assets/Wireframes/css%20validator.png)
Css was validated using the w3c validation service. The first run identified a missing comma in the font family causing the fallback font of sans serif to be used impacting readability.


**HTML validation**
![Image of HTML validation](/assets/Wireframes/html-validator.png)
HTML was validated using the w3c validation service. The first run identified one stray div closing tag which was then rectified.

## Deployment

### Deployment Process
This site was deployed using github pages by navigating to settings> pages then choosing to deploy from a branch and setting that branch to be main. 

## Reflection on Development Process


### Challenges
Describe any challenges faced when integrating AI-generated content and how they were addressed.

### Final Thoughts
Provide any additional insights gained during the project and thoughts on the overall process.  
**Guidance:** Begin drafting reflections during Phase 1 and update throughout the project. Finalize this section after Phase 4. Highlight successes and challenges, particularly regarding the use of AI tools, and provide overall insights into the project.

## Code Attribution
Properly attribute any external code sources used in the project (excluding GitHub Copilot-generated code).  
**Guidance:** Document any external code sources used throughout the entire project, especially during Phase 2 and Phase 3. Exclude GitHub Copilot-generated code from attribution.

## Future Improvements
Briefly discuss potential future improvements or features that could be added to the project.  
**Guidance:** Reflect on potential enhancements that could be made to the project after Phase 4: Final Testing, Debugging & Deployment. These could be Could user story features you didn’t have time to implement or improvements based on testing feedback.