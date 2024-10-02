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

![plot](/ReadMe_Resources/Wireframe%20MVP-initial.png)


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
I used balsamiq to generate the large display view for the site in low fidelity but did not create on for the mobile view as i was using bootstrap. Bootstraps use develops from a mobile first approach by their integration of flexbox, and so the main consideration for me was how the site would unfold into larger screens. I therefore decided not to spend time developing a mobile view as the site would naturally collapse due to bootstraps flexbox integration. 

The file below show the balsamiq wireframe based on the initial two panel toc design. As discussed earlier this approach deemed too difficult for my current skills and I was forced to adapt the design post design.  I did however, maintain the general theme as shown in the wireframe when developing the Minimum Viable Product (MVP). The Nav/Footer as well as the main content are the same as in the coded MVP. I did however, as a later design decision, move the 'signup banner' down to above the footer as it did not seem to fit the flow once coded.

The balsamiq wireframe also contains my original design notes.
![plot](/ReadMe_Resources/balsamiq-Desktop-view.png)

### Accessibility Considerations
There is still a lot of work to do for accessibility considerations for this site. In particular the colour pallet is currently only considered as temporary as discussed in the design section. Therefore colour challenges to users are not optimal.

I also intend to review the code for better usage of aria labelling.

## AI Tools Usage
No AI were harmed in the making of this website.

### DALL-E
DALL-E Not used.

### ahrefs

## Features Implementation
### Core Features (Must-Haves)
The following feature have been implemented:
1. collapsing nav bar menus (triggered on size size)
2. go-to-the-top button added to the footer to help avoid scrolling back up to the top of the site
3. accordion section with collapsing informational sections
4. cards were used to organise information next to a relevant engaging image
5. Modal form to trigger sign up form inputs
6. location map embedded into iframe.

### Advanced Features (Should-Haves)
**Feature 5:** The site should implement a mood switch similar to a dark/light mode switch, which allows the user to customised the site appearance based on their mood.

### Optional Features (Could-Haves)
**Feature 1:** A mood switch function to allow the user to customise the site to suit their mood. like dark/light mode but tailored to be happy/moody modes which would effect the lighting, colours etc.

**Feature 2:** Video Gallery which returned tailored results based on a search query
**Feature 3:** Music Gallery which returned tailored results based on a search query
**Feature 4:** Reading Gallery which returned tailored results based on a search query

## AI Tools Usage
No AI used throughout the project

### GitHub Copilot
Github Copilot was not used on this project.

## Testing and Validation
### Testing Results
The following testing on the deployed environment were performed:
1. All links were tested in the live environment and are currently work. Testing all links did however identify that I had forgotten to add social media links to 3 of the 4 cards in the 'meet our team' section.
2. Tested the navigation to the other pages and the return path home.
#### Unresolved/Known Issues:
1. There is a modal button problem that I have not been able to fix. The modal button does not close when selecting either of the close options. This is a know issue in BS 5.3 and can be immediately migrating the code to bootstrap 4.x
2. The 'subscribe to newsletter' button currently does nothing. will probably convert to js later on. 

### Validation
HTML code was validated using w3.org validator. The result returned errors as follows:
1. line 19 had a double `<<link` as opening tag. **FIXED** 
2. line 229: a file path used as a link contained spaces `**<img src="/assets/images/Mind Based Info-Graphic Template.jpg" alt="" class="img-fluid">**` **FIXED**
3. line 757: Bad value `close` for attribute `type` on element button **FIXED** replaced 'close' with type 'button' 
4. line 736: - `**<label for="repreatPassword"> Repeat Password`</label> **IGNORED** `<label for` is used by bootstrap 5.3 as part of form controls
5. line 744: - `**<label for="repreatPassword"> Repeat Password`</label> **IGNORED** `<label for` is used by bootstrap 5.3 as part of form controls
6. Warning: Line 81: `Consider using the `h1` element as a top-level heading only (all `h1` elements are treated as top-level headings by many screen readers and other tools)` **FIXED** h1 currently used to maintain text size. will fix with .css. Added as Issue 19 to Backlog in Project Board. The issue was due to Bootstrap Modal dialog using H1 for the dialog title. I updated the modal element to use H2 instead and now the validator passes on this issue.

#### CSS Stylesheet:
There were no validation errors found using w3.org css validator

## AI Tools Usage
The only use of AI on the project was for the generation of user bios for the counsellors section.
The following site creates fake bios using keywords: https://ahrefs.com/writing-tools/bio-generator.

### GitHub Copilot
Not used

## Deployment
The site was deployed on Github pages using steps provided in LMS walkthrough project. See steps used below.

### Deployment Process
- Steps
    1. Go to the **Settings** tab of your GitHub repo.
    2. On the left-hand sidebar, in the **Code and automation** section, select **Pages**.
    3. Make sure:
        1. **Source** is set to 'Deploy from Branch'.
        2. **Main branch** is selected.
        3. **Folder** is set to / (root).
    4. Under Branch, click **Save**.
    5. Go back to the **Code** tab. Wait a few minutes for the build to finish and **refresh your repo.**
    6. On the right-hand side, in the **Environments** section, click on 'github-pages'.
    7. Click **View deployment** to see the live site. The URL will look similar to **YOUR-USERNAME.github.io/love-running**.

## AI Tools Usage
No AI tools used

### Reflection
The development of this site was a great learning experience and the tight timescales replicated the importance of having an initial sketch in mind as early as possible. I found that wireframing helped prevent feature creep, because as a new developer I was eager to try out multiple things. I learned early on about the importance of MVP and how all possible updates, enhancements and additions to the design should be left until after the MVP has been achieved.

I did not use any sort of AI assistance as I believe that its usage, at this stage of my career would limit my ambition of being a great coder in the future. I will hope to utilise AI once I am confident of the underlying principles of the coding languages I am learning.

## Reflection on Development Process
### Successes
My success was a relative small one in that I am pleased that I was able to build an MVP site based on a small brief with only 20 days coding experience. (I'll take the small wins for now).

### Challenges
My major challenge came about because of my initial designs use of side panelled table of contents. This required Bootstraps ScrollSpy which I did not have time to master.

My other challenge was of a more basic nature and was related to the placement of items at exact locations on the page. I felt that with Bootstrap I had to settle for approximate locations for the placement of items but I could have spend hours moving things one pixel at a time.

I had a lot of issues getting the modal dialog to work and wasted a lot of time trying to debug why the top right hand side close button was permanently left side aligned. After a lot of time playing with the code, I turned to google. in researching the issue I became aware of a know issue with version 5.3 of bootstraps where this bug is documented.

Really the biggest challenge was getting over the shock of a blank design and my self-doubt (considering I have only been coding for 20 days, I forgave myself on that one). I found that getting something down, how ever small, even if it was a simple button, kick started my process. The next challenge after that was trying to stop myself from continually tinkering with the code. so starting is hard, but stopping seems harder.

### Final Thoughts
My main takeaway from this project was the creative block I experienced looking at a blank page. I have learned that starting on the smallest component/element kickstarts the process. However, I also learned that stopping is equally hard, and that keeping in mind the MVP principle is really important.

## Code Attribution
I did not use any AI assistance on this project as I feel it would defeat the point of me being on this course, which is to learn to be a competent full stack developer. Once I have the necessary coding skills I would certainly consider using AI to assist in the development process.

Most of my assistance with the coding was gained by reviewing the 3 LMS walkthrough projects. In addition I heavily references w3.org and the bootstrap website.

My initial framework for the site was developed by watching YouTube videos on layout and where I was stuck, trying to find walkthrough examples. In particular I was heavily influenced by Youtuber "Traversy Media" whose walkthrough video provided me with the basics of my MVP. I did however feel that I wasted a lot of time doing this but largely put that down to the nerves of facing a blank sheet design for the first time. I am confident that once I have some experience coding, that I would then start to consider some of the tasks for developing a site quite repetitive and therefore less challenging.

All  my images were sourced from free online resource with the following attributations.
- Navbar background: peterschreiber.media; from istockphotos
- community matters card: diversity-2-1184116.jpg: Photo by <a href="/photographer/spekulator-53353">spekulator</a> on <a href="/">Freeimages.com</a>
- your dome is your home card: mind-based-info-graphic-template-5188651.zip: Image by <a href="/">Freeimages.com</a>

## Future Improvements
There are a number of improvements that could be made for the site. These include;
- a redesign of the colour pallet for the entire site to aid with accessibility
- the development of the linked pages (video, reading, and music)
	- The music page as to provide embedded media plays in a gallery format with a search function that allowed the user to filter on types of music (e.g meditation music, yoga music, etc.) with the search limiting the embedded media players displayed based on the search results
	- The video page was to be the same format as the music page but with embedded videos.
	- The reading page was to have the same search functionality but would return a search based on the type of reading required (e.g scholarly, blog, pdf books etc.)
- I am not sure if it is even possible but i wanted the accordion section to refresh the quote on a regular basis so that the site did not become static and act as an evolving landscape for the user each time they visited.
