![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# The Mental-Well. *The knowledge well for your mental well being*

## Overview
The Mental-Well is a website which seeks to provide mindfulness information and resource links which is presented in a supportive and organised layout, using a clean design supplemented by a calming colour pallet.  

Addition pages will be developed in future to include a dedicated;
- reading page (selected articles, news links, blog posts and research pages)
- video library page (a gallery of videos)
- meditation based music page (media embedded gallery page).

### Purpose
The site's aim is to present information which is simple and jargon free; that avoids technical or complicated language; and attempts to avoid over nesting in order to avoid the user 'going down rabbit holes' in search for the relevant required resource, specific to that site visits goal. We hope that the site is a place that users choose to return, and with that in mind, we wish to make each visit uniquely relevant. This is because mental health and wellness needs are never static and can take may different forms and symptoms, even changing hourly for some.    

### Target Audience
The target audience for the site will be individuals looking for a centralised source of information which gathers mindfulness focused videos, scholarly papers, music links, and community support. 

The site also target freelance mindfulness counsellors as a site from which they can offer their services. As such the site has sections dedicated for freelance mindfulness counsellors to provide their services. This feature is currently only presenting four options. 

## User Stories
### Site Actors
1. Users seeking wellness, mindfulness and mental health information
2. Freelance counsellors seeking to showcase their business.
3. Site developer/designer seeking to develop a low maintenance and appealing site 

### User Stories
**USER STORY #1:** As a user I want access basic, user friendly information on mindfulness and mental health issues, which is presented in a beginner friendly and accessible way.

**USER STORY #2:** As a counsellor I want a prominent place on the site to show case my offerings 

**USER STORY #3:** As a user I want to access a site which is presented by a clean and supportive design

**USER STORY #3**: As the site designer I want to restrict the initial MVP to only HTML, CSS and Bootstrap

**USER STORY #5:** As the site designer I want to present a calming, well-organised user experience.

**USER STORY #6:** As a user I want the site to utilise all accessibility enhancements

**USER STORY #7:** As a user I want access to positive affirmations which update on each visit

**USER STORY #8:** As a user I want access to a searchable video library presented in a gallery format, which filters the offerings based on my search criteria.

**USER STORY #9:** As a user I want access to a searchable video music presented in a gallery format, which filters the offerings based on my search criteria.

**USER STORY #10:** As a user I want access to a searchable reading library presented in a gallery format, which filters the offerings based on my search criteria.

### Must-Have User Stories
**USER STORY #1:** As a user I want access basic, user friendly information on mindfulness and mental health issues, which is presented in a beginner friendly and accessible way.

**Acceptance Criteria:** 
1. The site is intuitive to navigate
2. The site uses a clean uncluttered design
3. The site clearly identifies the purpose of each section via informative titles

**USER STORY #2:** As a counsellor I want a prominent place on the site to show case my offerings 
**Acceptance Criteria:**
1. The site uses cards to presented a summary of each counsellor where by they can provide a brief bio and social media links.

**USER STORY #3:** As a user I want to access a site which is presented by a clean and supportive design.
**Acceptance Criteria:**
1. The site will be laid out using Bootstrap grid system
2. the site will utilise cards and cascades to group information
3. the site will utilise accordion to compress information and avoid clutter

**USER STORY #4:** As the site designer I want to restrict the initial MVP to only HTML, CSS and Bootstrap.
**Acceptance Criteria:**
1. The site will be built using html, css and bootstrap only

**USER STORY #5:** As the site designer I want to present a calming, well-organised user experience.
**Acceptance Criteria:**
1. The site will use a calming colour pallet
2. the site will provide user customisation for the site mood similar to a dark/light mode swithc

**USER STORY #6:** As a user I want the site to utilise all accessibility enhancements
**Acceptance Criteria:**
1. the site will utilise alt narrative throughout

### Should-Have User Stories
**USER STORY #8:** As a user I want access to a searchable video library presented in a gallery format, which filters the offerings based on my search criteria.

**USER STORY #9:** As a user I want access to a searchable video music presented in a gallery format, which filters the offerings based on my search criteria.

**USER STORY #10:** As a user I want access to a searchable reading library presented in a gallery format, which filters the offerings based on my search criteria.

### Could-Have User Stories
USER STORY #7: As a user I want access to positive affirmations which update on each visit

## Design Decisions
The initial design was to have a left aligned site table of content panel, and a right aligned 'on this page table of content page' for easy navigation as the site grows. This layout was modelled on the Bootstrap 5 home page which uses the same approach. This concept was expected to look like this...
![Initial Wireframe MVP] (/ReadMe_Resources/Wireframe MVP-initial.png)

![Image caption](/ReadMe_Resources/Wireframe MVP-initial.png)

However, this approach was dropped for an 'out of the box' mobile friendly layout, and the side panel version pushed for later consideration. This decision was made mainly due to time constraint not allow for the effort of design how the side panels would collapse when in mobile view. Additionally, the use and knowledge of 'Scrollspy' is required, with the learning also addition to lost time.

The colour themes for the site have not currently been achieved and will be required for future updates. The intention is to use the same colour palette as those used at this site: [Smashing Magazine](https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/) This site used a shade of green (which I found difficult to replicate) white text and an orange-brown for headings (which i also found difficult to replicate). I did however utilise the rainbow text effect used on this sites title, by using .css to style using linear gradient and background clip.

It was also my intent to use the [Smashing Magazine](https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/) use of embedded the toc into the main body, but this was abandoned after a few attempts as I could not make it work in mobile view.

I decided to use the following global design rules:
1. Rule of thirds to apply throughout. both vertically and horizontally.
2. Nav bar and footer bar were to use the same background
3. colour pallet for the site was to be darker hues resembling those used on [Smashing Magazine](https://www.smashingmagazine.com/2021/03/complete-guide-accessible-front-end-components/)
4. main content was to be presented in cards to avoid overwhelm for the user
5. A mood switch function to allow the user to customise the site to suit their mood. like dark/light mode but tailored to be happy/moody modes which would effect the lighting, colours etc.

Lastly it was my intent to use Bootstrap Jumbotron as a main  element on the site, but this feature has been removed from Bootstrap 5. It is recommended that styling is used to recreate the jumbotron effect, but I only realised its omission from BS5 at a later stage in the development process. 

### Wireframes
Include wireframes for key sections of your website.  
Briefly describe the design choices, including layout, colour schemes, and fonts.  
**Guidance:** Start this section during Phase 1: Ideation & Initial Setup and update it throughout Phase 2 and Phase 3. Include digital wireframes created in Phase 1. Document the reasoning behind your layout choices, colour schemes, and font selections.

### Accessibility Considerations
Discuss how accessibility guidelines were adhered to, including colour contrast and alt text for images.  
**Guidance:** Outline how you've incorporated accessibility into your design, ensuring that your project adheres to guidelines such as WCAG.

## AI Tools Usage

### DALL-E
Describe how DALL-E was used for image generation, including examples of successes and challenges.  
**Guidance:** Specifically mention how you used DALL-E for image generation and the impact this had on your design process.

### ahrefs
I used this site to generate fake bios for the site. The site uses AI to generate social media bios based on keywords. The site worked really well and i think with more detailed keywords, the results could have been more detailed.

## Features Implementation

### Core Features (Must-Haves)
- **Feature 1:** Description of the implemented feature.
- **Feature 2:** Description of the implemented feature.

(Include all must-have features)  
**Guidance:** Use this section as you complete Phase 2: Must User Stories Implementation & Testing. Document all the must-have features you implemented, explaining how they align with the user stories and acceptance criteria.

### Advanced Features (Should-Haves)
- **Feature 1:** Description of the implemented feature.
- **Feature 2:** Description of the implemented feature.

(Include all should-have features)  
**Guidance:** Include any advanced features you implemented during Phase 3: Should User Stories Implementation & Any Advanced Features. Explain how these features enhance user experience and their alignment with the acceptance criteria.

### Optional Features (Could-Haves)
- **Feature 1:** Description of the implemented feature (if any).
- **Feature 2:** Description of the implemented feature (if any).

(Include any could-have features that were implemented or considered)  
**Guidance:** If any could-have features were implemented, describe them here. This is an opportunity to showcase extra work done beyond the initial scope. But remember - keep it simple! Focus on the Must stories first. Could user story features are commonly earmarked for future project iterations.

## AI Tools Usage

### GitHub Copilot
Describe how GitHub Copilot assisted in coding, including any challenges or adjustments needed.  
**Guidance:** Reflect on how GitHub Copilot assisted in coding, particularly any challenges or adjustments that were needed to align with project goals.

## Testing and Validation

### Testing Results
Summarize the results of testing across different devices and screen sizes.  
Mention any issues found and how they were resolved.  
**Guidance:** Summarize the results of your testing across various devices using tools like Chrome DevTools, as outlined in Phase 2. Mention any issues found and how they were resolved.

### Validation
Discuss the validation process for HTML and CSS using W3C and Jigsaw validators.  
Include the results of the validation process.  
**Guidance:** Document your use of W3C and Jigsaw validators to ensure your HTML and CSS meet web standards. Include any errors or warnings encountered and how they were resolved.

## AI Tools Usage

### GitHub Copilot
Brief reflection on the effectiveness of using AI tools for debugging and validation.  
**Guidance:** Reflect on how GitHub Copilot assisted with debugging and validation, particularly any issues it helped resolve.

## Deployment

### Deployment Process
Briefly describe the deployment process to GitHub Pages or another cloud platform.  
Mention any specific challenges encountered during deployment.  
**Guidance:** Describe the steps you took to deploy your website during Phase 4: Final Testing, Debugging & Deployment, including any challenges encountered.

## AI Tools Usage

### Reflection
Describe the role AI tools played in the deployment process, including any benefits or challenges.  
**Guidance:** Reflect on how AI tools assisted with the deployment process, particularly how they streamlined any tasks or presented challenges.

## Reflection on Development Process

### Successes
Effective use of AI tools, including GitHub Copilot and DALL-E, and how they contributed to the development process.

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
