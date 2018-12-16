# CineGrub | where restaurants and movies come together

Massive Front-end Project **(Project Duration: 2wks)**

### Group Team Members

- David Padilla
- Ksenia Malysheva
- Hannah Shaw
- Keiran Hamilton

### Link to Website

www.cinegrub.com

**Browser compatibility checked with:**

- Google Chrome - Version 70.0.3538.77 and up
- Firefox Developer Edition - 64.0b8 (64-bit) and up

### Assignment

I was tasked along with my team members to come up with a website idea and have a
working MVP ready within two weeks for presentation. I can confidently say that
we have created a fully functional MVP within the deadline and met all of our stretch
goals as well. I personally came up with the website proposal of CineGrub after
exploring potential APIs for inspiration. I kept coming back to the MovieDB and Zomato
API. As a moviegoer, I enjoy being able to take my wife out to both a movie and
dinner. And so the idea was to make both of these services come together and feel
seamless within a centralized search engine.

### Skills Learned

I pushed myself harder than I ever had before in this project and learned so much along the way.
With being only a third way done with the class, I can honestly say I feel super comfortable
in the role of a Front-end Web Developer. Here are some of the skills I learned during the course
of this project.

- Integration w/ **new** Third-party Libraries (anime.js, Formspree, SweetAlert2)
- Google Maps (Geocoding API, Maps Static API, Maps URLs)
- CSS Flip Animation
- ZIP Code Validation
- Dynamic Contact Form
- Preloader
- Resolving Merge Conflicts
- Reviewing Pull Requests
- Connecting Custom URL to GitHub Pages

### Technologies Used

HTML5, CSS3, Javascript, jQuery, Bootstrap 4, Google Fonts, (3) Google
Map APIs (Map Static API, Geocoding API, Maps URL), anime.js, JSDelivr,
Font Awesome 5, Zomato API, MovieDB API, SweetAlert2, Firebase, Moment.js,
(2) Fandango (hack) APIs, Formspree.

### My Challenges

- JavaScript Maps API
- This API proved more difficult to implement, and therefore I compromised
  on three other Google Map APIs to compensate for the functionality that
  existed within the Javascript Maps API.

- ZIP Code Validation
- Getting the ZIP Code validation to work was really tricky, but utlimately I
  was able to create three nested else-if statements to filter out the wrong ZIP
  Codes by comparing their properties within their JSON data.

- Zomato API _q parameter_
- The _q parameter_ proved to be the toughest challenge for me because it didn't
  offer the best coverage per ZIP Code searched. It would restrict ZIP Codes
  based on my personal location. A sort of cookies issue. I resolved this by using
  the _lat & lng parameters_ instead, which removed all hiccups that the API request
  was producing.

### My Contributions

I was in charge of the overall CSS for every aspect of the website. Creating the layout, the animations,
dynamic elements, API formatting, and typography. Aside from the visual aspect of the website, I created
the functionality for the submit button, the loading icon, Google Maps API with AJAX, fixing user
authentication bugs, and enhancing the Zomato & MovieDB APIs with star ratings using Font Awesome 5.
_(Also, feel free to check out https://github.com/shawhannah/project-1 to validate my branches/commits)_

### Future Features (had more developmental time been given)

- Mobile Responsiveness
- Enable Email Invitations & Notifications
- Social Media Presence on Social Platforms (Instagram, Facebook, Twitter)
- Convert from Manual Authentication to Firebase Authorization

### Closing Comments

I'm very pleased with how the final product came out. I got to collaborate with team members of unique
personalities and skillsets. There was alot more I wish we could've done like creating a social media
presence on other social platforms. There are however understandable limitations to the project as well.
Because it serves as a portfolio project made by aspiring developers, high traffic volumes would be
detrimental to the Google Maps feature because it depends on dozens of call requests per search that cost
money. I do feel like this portfolio project is something that I will pursue to make public with more
features long after my class is finished on the side independently.

_created by David M. Padilla_
