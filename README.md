
# Project Portfolio 1 - Phil Lynott Archive

The Phil Lynott archive is a fully responsive site for people to read and submit stories about Phil's life. 

<img src="/assets/css/images/amiresponsive.png">

[You can view my website here](https://jasonhorgan.github.io/Project-1/)

** Shields.io badging here ** 



# User Experience (UX)

### Initial Discussion

The Phil Lynott Archive is an online Archive highlighting the story of Irish Rock legend Phil Lynott. The purpose of this site is to document the achievements of Phil where people can submit their stories and photos of Phil so future generations can look back and learn more about who he was.


#### Key information for the site

- Who is Phil Lynott
- Why is he Famous
- What bands was he in
- Stories of Phil from people who knew him
- Photographs of him
- Videos of him

### User Stories

#### Client Goals

- To make it easy for members to learn more about what Phil was really like 
- To  make it easy for members to learn more about the music he created 
- To make it easy for people to contribute to the archive 
- To make it easy for members to contact us with questions or suggestions

#### First Time Visitor Goals

- I want to learn more about who Phil Lynott is 
- I want a lot of information about Phil and his music to be available in the one place 
- I want to find where I can see more Phil Lynott content on social media such as Instagram

#### Returning Visitor Goals

- I want to find new stories about Phil that were previously unknown
- I want to find contact info for whoever runs the archive to ask about submitting my own story

#### Frequent Visitor Goals

- I want to submit my own story to the archive 

For my first project Portfolio I have created an online Archive highlighting the story of Irish Rock legend Phil Lynott. The purpose of this site is to document the achievements of Phil where people can submit their stories and photos of Phil so future generations can look back and learn more about who he was.
## Design

### Color Scheme 

<img src="/assets/css/images/phil_color_scheme.jpeg"/>


The Website uses a Color Palette of colors extracted from the hero image which I got from Adobe Color, as seen below. This helped the website maintain consistency throughout. 

<img src="/assets/css/images/adobe_color.png">

### Typography

Google Fonts was used for the following fonts:

- Merriweather is used for headings on the site. It is a serif font.

- Raleway is used for the body text on the site. It is a sans-serif font.

### Imagery 

Images were used with the permission of the owners and taken from royalty free sites. 

### Wireframe 

The Wireframe was created using Balsamiq and can be viewed here (insert balsamic link here)

### Features

The website is comprised of four pages, three of which are accessible from the navigation menu (home page, books page & contact us page). The fourth page is a thank you page which is shown once a user submits the form on the contact us page.

All Pages on the website have:

- A responsive navigation bar at the top which allows the user to navigate through the site. The Nav bar contains links to the home page, gallery, video section and the submit section. When viewing with mobile devices the navigation links change to a burger toggler. This is typically seen on mobile sites and makes for a better user experience. 

A footer which contains social media icon links to instagram, Facebook, X and Youtube. I used icons to identify the websites and when the user clicks on them, they are taken to a new tab so they do not lose my site. 

### Home Page.

The home page is the main page of the site at the moment. This is where the user will find a lot of information and read other user stories about who Phil Lynott was, as well as other interesting facts about him. There are also a number of photographs with alt text included for accesibility.

### Gallery 

The gallery features a number of photographs of Phil Lynott over the course of his life.

### Videos

The video section contains music videos of Phil Lynotts most popular songs, as well as interviews about him to give the user more context of who he was as a person. 

### Submit

The submit section of the website contains a form where users can submit stories detailing interactions regular people had with Phil over the course of his life so these stories are not lost over time. 

### Future Implementations

In the future I would like to implement the ability for users to upload photos and videos to be featured on the site. 

### Accessibility

I have attempted to make the site as user friendly as possible by 

using alt text to describe images, ensuring the text is readable by placing it over contrasting color backgrounds, as seen in the hero image on the home page. 

## Technologies Used

### Languages used 

I used HTML and CSS for this site. 

### Frameworks, Libraries & Programs Used

Balsamiq - to create wireframes.

Github - To store and deploy the site.

Google Fonts - To import the fonts on the site.

Font Awesome - For all icons on the site such as hamburger icon in the nav bar and the social media icons in the footer.

Google Developer Tools - to assist with styling all of the pages on each device type.

[Favicon.io](https://favicon.io/) To create favicon.

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on a range of devices.

## Deployment & Local Development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

- Go to the Settings tab of your GitHub repo.
- On the left-hand sidebar, in the Code and automation section, select Pages.
- Make sure:
    Source is set to 'Deploy from Branch'.
    Main branch is selected.
    Folder is set to / (root).
- Under Branch, click Save.
- Go back to the Code tab. Wait a few minutes for the build to finish and refresh your repo.
- On the right-hand side, in the Environments section, click on 'github-pages'.
- Click View deployment to see the live site. The URL will look similar to YOUR-USERNAME.github.io/project-name.

## Testing

I tested the code all throughout the development of the site using different screen sizes and dev tools was a massive help for this. 

The following issues were raised during my mid project meeting with my mentor:

- About mid way through the project, I realized that I had not styled the page with a mobile first approach and the site was not behaving the way I wanted it to. As a result, I deleted and re-designed the majority of the main content on the index.html file. In doing so, I made a lot of deletions and additions in the one commit, which I now understand is not good practise. This can be seen on commit reference "96f52f5"

- I had issues styling the YouTube videos on the videos.html page, but after a lot of trial, error and googling, I was able to style the videos to be responsive on all device types. 

- The H2 and H3 text on the home page was not readable due to the text colours blending with the background image but this was fixed by adding a contrasting, slightly transparent background colour to make the text more readable. 

### W3C Validator

I used W3C validator to validate all HTML and CSS code. There was info messages as seen in the screenshots, but no errors are present. 

- [Index Page HTML] <img src="/assets/css/images/index_w3_validate.png">
- [Gallery Page HTML] <img src="/assets/css/images/gallery_w3_validate.png">
- [Video Page HTML]<img src="/assets/css/images/video_w3_validate.png">
- [Submit Page HTML]<img src="/assets/css/images/submit_w3_validate.png">
- [style.css CSS]<img src="/assets/css/images/style_css_validate.png">



