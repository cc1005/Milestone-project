# Conor Campbell Portfolio
First milestone Project: User-Centric Frontend Development - Code Institute

This website is functioning as a mock-up of a website I will later create with copyrighted assets for an academic forum based in Ireland. This forum puts on annual events, and helps publish books on certain types of history. The website will contain information about the forum, details of the annual conference & other events, links to publications and conference posters, as well as contact details for the forum itself.

See the directory entitled "resources" for wireframes and handwritten development documents.


## UX
Given that many of the visitors to the website will not be particularly technically savvy (given the academic demographic of the target audience), the website will be designed as simply as possible, with little in the way of complicated transitions or changing/morphing elements. This is why I have opted for a simple, single-scrolling page with internal links in the Navbar.

The colour palette will be reserved to reflect the serious nature of the content. Fictionalised posters have been used to create the colour scheme for the project (see "resources" directory in github), one of which is also produced in the final website. These posters were made using the website https://www.canva.com/. The website https://coolors.co/, recommended by another Code Institute graduate, was used to generate a colour scheme which I subsequently modified - again, see the "resources" directory for this colour scheme.

Many of the above decisions were taken with the advice of my mentor, with whom I had three meetings over the course of the project.

User stories:
- Less technically able, academic type: this user will encounter a simplified website with variable type size depending on the browser size. The reserved colour scheme and limited moving parts of the website will provide for a reliable experiences with no surprises, as will the single-page layout which requires no knowledge of website navigation.

- More technologically aware, younger users: this is not necessarily the target demographic, but I believe these users will still have an engaging and useful experience with the website. The information is laid out clearly and consistently, and while the colour design is reserved I believe it has its own internal consistency and style that works for the brand. Additionally, the social media links for The Irish Newspaper Forum are highlighted in the navigation bar and given prominence in the footer.

## Technologies
1. HTML
2. CSS
3. Bootstrap (4.3.x)


## Features

Collapsable navbar: The website features a collapsable navbar that turns into a right-aligned hamburger list under bootstrap's "md" size, the standard transformation size for the website. This navbar links to the relevant sections on the page, and the bottom title in the footer links back up to the top, allowing for intuitive and convenient navigation.

Fully reactive: Both bootstrap elements and custom media-query CSS have been used to create a fully reactive website, focussed primarily on the difference between xs/sm devices and any larger. Various elements are phased out in the smaller screen sizes (see especially the second picture of glasses on a newspaper in the title bar) while text sizes also modify to fit the screen (often using custom breakpoints to ensure no overlap with other elements). In the Publications section there is also a matched partially transparent colour mask for half of the image, a fairly complicated effect that required quite a bit of work to keep consistent over all sizes. Thorough testing of the website ensured that these reactive elements remained consistent throughout.

Sign-up bar: This section allows the user to use forms to supply their information for a newsletter. In future versions of the website (after I have studied back-end programming) this could obviously be linked up to a real database for storing this information.


### Features Left to Implement

As I move further through the course, I will look to implement features into the website that are impossible at this stage. Specifically, I will provide the back-end resources to store and sift through users signing up for the newsletter.

## Testing

This project has been tested manually, as there have yet to be any instructions in the Code Institute course on how to automatically test websites. I have made sure that all the links work and that the website is fully reactive, running it through a series of screen sizes and varied dimensions. I have also consulted with friends and relatives as to the merits of the project, and demonstrated aspects of it to my mentor who gave me extensive recommendations on how to improve it.

Several bugs and breaks were encountered during the testing process. The topbar in particular proved very difficult to align, and forced me to develop my understanding of breakpoints and how to vanish elements under certain sizes. Originally, both headbar images crushed together in mobile view, and I had to introduce the classes 'd-none d-md-block' to force its disappearance on smaller screens. The navbar's alignment also proved tricky: expanding it out to fit the container seemed simple at first, but as did a lot of aspects of the project it required a great deal of tinkering in custom CSS to get it to a position I was happy with.

I needed to develop my understanding of the meaning of "container-flex" elements in Bootstrap. A fairly constant concern early in the project was that many of my elements would not spread across the whole width of the screen, maintaining an inexplicable margin on the right hand side of the screen. This was only resolved by using the "container-flex" class.


## Deployment
This site is hosted on GitHub and published through GitHub pages. This website will be updated directly through the master branch.



## Credits

Advice and for the original navbar positioning (specifically "Navbar 4") was taken from https://www.codeply.com/go/qhaBrcWp3v.

The source code of many of the Code Institute example projects was used as inspiration for many of the elements in this project.

Bootstrap documentation has, of course, proven invaluable, and for the navbar in particular modified versions of the documentation provided on the bootstrap website have been used.

### Content
All content, unless specifically acknowledged otherwise, was written by me.

### Media
All photos were taken from [Pexels](https://www.pexels.com/), a stock image library. Credit to The Atlantic, whose video is embedded in the media section, and Desmond Shearer's Irish History podcast. These media items are hosted on Youtube and Soundcloud respectively. All other business names are used respective of their trademarks, and the 'University of North-Eastern England' is a fictitious university.

### Acknowledgements
