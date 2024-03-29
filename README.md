
# Project Portfolio 1 - Phil Lynott Archive

The Phil Lynott archive is a fully responsive site for people to read and submit stories about Phil's life. 

<img src="/assets/images/amiresponsive.png">

[You can view my website here](https://jasonhorgan.github.io/Project-1/)

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

<img src="/assets/images/phil_color_scheme.jpeg"/>


The Website uses a Color Palette of colors extracted from the hero image which I got from Adobe Color, as seen below. This helped the website maintain consistency throughout. 

<img src="/assets/images/adobe_color.png">

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

<img src="/assets/images/home_read.png">

### Gallery 

The gallery features a number of photographs of Phil Lynott over the course of his life.

I decided not to include any text in this page as I did not want it to take away from the impact of the photos and I feel that a gallery should speak for itself. 

<img src="/assets/images/gallery_read.png">

### Videos

The video section contains music videos of Phil Lynotts most popular songs, as well as interviews about him to give the user more context of who he was as a person. Again, I decided against using text in this section as I wanted the users to focus on the content of the videos. 

<img src="/assets/images/video_read.png">

### Submit

The submit section of the website contains a form where users can submit stories detailing interactions regular people had with Phil over the course of his life so these stories are not lost over time. 

<img src="/assets/images/submit_read.png">

### Thank you

I added a thank you html page which will pop up for users when they submit the form on the submit page. This Thank you form is set to automatically close after 10 seconds. 

<img src="/assets/images/thank_read.png">

### 404 

I added a 404 page which will pop up if the user enters the page with an incorrect URL. I included a reference to a thin lizzy song in this, so the user will have a good experience, even when they have a bad one with a broken link. 

<img src="/assets/images/404_read.png">

### Future Implementations

In the future I would like to implement the ability for users to upload photos and videos to be featured on the site. 

### Accessibility

I have attempted to make the site as user friendly as possible by using alt text to describe images, ensuring the text is readable by placing it over contrasting color backgrounds, as seen in the hero image on the home page. 

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

[Am I Responsive?](http://ami.responsivedesign.is/) To show the website image on different size devices.
[Convertio](https://convertio.co/) To convert images from JPG to WEBP

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

- Index Page HTML <img src="/assets/images/index_w3_validate.png">
- Gallery Page HTML  <img src="/assets/images/gallery_w3_validate.png">
- Video Page HTML <img src="/assets/images/videos_w3_validate.png">
- Submit Page HTML <img src="/assets/images/submit_w3_validate.png">
- style.css CSS <img src="/assets/images/style_css_validate.png">

### Solved Bugs 

- I had a bug when I initially had the videos and photographs in the Gallery page where the sizing of the photos was affected by the videos being in the same div. After some testing, I decided that I would make a new page for videos as this allowed me to style them easier and also allowed for a better user experience when someone is navigating the site. 

- I had a bug where there was overflow on the videos page on mobile screens because the width of the videos was larger than a phone screen. I was able to correct this with the width settings in css. 

I also encountered a bug, after I corrected my file directory to place the image folder outside the css folder, where my hero image would not load on my deployed site. I fixed this by placing a link to my github repo as the image url.  


### Lighthouse Testing 

I used the lighthouse function in chrome developer tools to test the performance, accessibility, Best practices and SEO of my site. 
Accessibility, Best practises and SEO all mostly scored 100, or very close to it, however the performance sometimes suffers on a couple of the pages, as demonstrated in the below screenshots. 

- Index mobile and desktop results <img src="/assets/images/index_desktop_lighthouse.png "> <img src="/assets/images/index_mobile_lighthouse.png">
- Gallery mobile and desktop results <img src="/assets/images/gallery_desktop_lighthouse.png" > <img src="/assets/images/gallery_mobile_lighthouse_80.png" >
- Video mobile and desktop results <img src="/assets/images/video_desktop_lighthouse.png" > <img src="/assets/images/video_mobile_lighthouse_84.png">
- Submit mobile and desktop results <img src="/assets/images/submit_desktop_lighthouse.png"> <img src="/assets/images/submit_mobile_lighthouse.png">

## Credits 

### Photo credits 

Please see full list of photo credits below:

- Phil_bar - https://www.rte.ie/archives/2016/0518/789174-old-town/
- Phil_bass - https://www.notreble.com/buzz/2015/05/01/bass-players-to-know-phil-lynott/
- Phil_bassbw - https://rockandrollparadise.com/phil-lynott-11986/
- phil_bw - https://www.bathroomwall.com/blogs/rock_blog/thin-lizzy-the-career-of-phil-lynott
- phil_bw2 - https://blackplaqueproject.com/biography/phil-lynott/
- phil_bw3 - https://denis.uk/artworks/categories/10/9550-thin-lizzy-phil-lynott-live-1977/
- phil_diner - https://www.chalkiedavies.com/blog/wnxarkyts2xeshnb2k5hfzsxnw3y3y
- phil_dogs - https://www.reddit.com/r/ireland/comments/lw0dw7/phil_lynott_in_response_to_the_list_doing_the/
- phil_guinness - https://imgur.com/gallery/xtTL62b
- phil_hero - https://www.theguardian.com/music/2012/sep/18/thin-lizzy-phil-lynott-interview
- phil_hotpress - https://www.telegraph.co.uk/music/artists/phil-lynott-addiction-destroyed-irelands-forgotten-rock-genius/

### Code Credits

I referenced multiple different resources as outlined below:

- Code Institute's "Love Running" walkthrough for Header, Nav bar, Footer, favicon and media query set ups. 
- This youtube video to help guide me through making a fixed hero image https://www.youtube.com/watch?v=0mYbVEBsMh8&t=15s
- W3 schools to help me understand a lot of fundamentals but specially the form element - https://www.w3schools.com/html/html_form_elements.asp
- Examples on how to write a readme, shared with me by my mentor Graeme, - https://github.com/kera-cudmore/readme-examples/blob/main/README.md and https://github.com/kera-cudmore/Bully-Book-Club/blob/main/README.md 
- Graeme for explaining how to add my own thank you html file in place of the Code Institutes form dump page. 
- Stack overflow forums for helping me when I was stuck on specific problems - https://stackoverflow.com/
- This YouTube video to help me understand how to style the YouTube videos on the video page - https://www.youtube.com/watch?v=jSVy-6kQDxY 

### Acknowledgments

My mentor Graeme for supporting me through the entire process and ensuring I was equipped with the right tools to overcome any issues during the project. 
The Code Institute slack community for being engaging and helpful when needed. 
Tutoring service for being on hand and keeping me on the right track when needed. 

