# Wonder Walkers
![Am I Responsive](/assets/images/readme%20images/am-i-responsive.png)

The static front-end website for a fictional group, known as the Wonder Walkers. This web page has been designed to promote the benefits of being outdoors and provide some inspirational guidance to its users. 

The site offers a homepage, based upon the who, what and why's of the group, followed by an equipment page, detailing some useful items for a productive outing. Also on offer, is a page dedicated to some walks undertaken by the group, along with its relevant information. Finally there is a contact us page, allowing users to get in touch with the group if they require help from external sources. 

The target user is anyone looking to become more active and offer suggestions on how to go about that. 

This site is part of a portfolio project, a series of five required to graduate with a diploma in full stack development from Code Institute

The site needed to be static and responsive, and incorporate using HTML and CSS programming languages.

## Design

![Initial design idea](/assets/images/readme%20images/wireframe-drawing.jpg)

This is how I originally wanted my webpage to look. I believe I have nearly achieved this, however I would have liked to have had more content separation. Everything looks to be in column, and whilst this makes the pages flow well, a contrasting row or two may have made it pop more.

### Navigation

![Nav bar top](/assets/images/readme%20images/nav-bar-1.png)


I wanted the site to be visually pleasing and simple to use with no complex menu or navigation link. It was important for me to have the navigation bar on the left hand side of the page, as it is unusual to see I felt it would stand out. Having it fixed to the screen throughout scrolling allows the user to easily navigate throughout the site, wherever they might be.

![Nav bar bottom](/assets/images/readme%20images/nav-bar-2.png)

The bottom navigation links all open up separate tabs to instagram, facebook and all trails sites. The black and white hiker image in the navigation bar gave inspiration for the color scheme. The colors chosen were `#383838` and `#f7f7f7`. Whilst this appears to be a safe option, I feel it works really well on the site and any further colors would look messy.

### Font

The font for the website remains present throughout with no deviation. The font chosen was "Encode sans” weight 300. I feel the text is readable throughout the site, but perhaps the font size could have been bigger for larger screens.

![Google Font](/assets/images/readme%20images/google-font.png)

### Images

I sourced the Images from Google. For the home page my search was for “families and individuals enjoying the outdoors”, as well as “disabled outdoor activities” for the thank you and contact us page. For our walks, I searched for the particular trails to select the pictures I wanted. On the equipment page, I am personally used to wearing the vibram shoes, so I wanted to incorporate the pair I own, as its description benefits from my experience. The other two images on the page were found through a google search.

### Hero Image
![Hero image](/assets/images/readme%20images/hero-image-and-heading.png)

The hero image came about through a similar search for my other images. I like how the color of the sky helps break the page up from its two-color scheme. Originally, I’d have liked the h1 element “Welcome to Wonder Walkers” to sit above the mountain with some opacity, however it works just as well in its current position. Maybe that could be a future development.

## Testing

### HTML
![HTML Validation](/assets/images/readme%20images/html-validate.png)

A test on the HTML code came up positive and threw no errors

### WAVE
 ![Wave test](/assets/images/readme%20images/wave-test-7.png)

Using WAVE, I had my site analysed and had no real errors in my code throughout the majority of the website.

![WAVE alerts](/assets/images/readme%20images/wave-test-3.png)

The alerts that crop up throughout the site deal with the underlining issues in my styling. An underlined piece of text tends to represent a link and I can imagine that a user of the page might feel that some of these are clickable (as some are). This is something to look in to in the future.

![WAVE error](/assets/images/readme%20images/wave-test-1.png)

An error occurs here on the contact us page. It appears as though the submit button sits below the footer. While it appears this way through validation, I have seen no sign of it when testing my site on a laptop or a mobile device. This issue requires further inspection.

### CSS
![CSS validator](/assets/images/readme%20images/w3c-css-validator.png)

I am pleased to see that no CSS errors were found.


### Lighthouse Testing
![Lighthouse 1](/assets/images/readme%20images/lighthouse-1.png)
![Lighthouse 2](/assets/images/readme%20images/lighthouse-2.png)
![Lighthouse 3](/assets/images/readme%20images/lighthouse-3.png)

The lighthouse testing threw up some good scores, and I am pleased with this.

### Unicorn revealer

I was made aware of the chrome extension [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln) that showed me particular issues with the layout of my site.

![Unicorn revealer](/assets/images/readme%20images/unicorn-revealer-1.png)

The unicorn revealer adds “sparkles” as a guide to where the layout of my site might hit some issues on different responsive devices. An incredibly useful extension.

### Web browsers
I used both Google Chrome and Safari to view my web page, and I could see no issues on these two browsers when opening the various links I had throughout the site

![Chrome](/assets/images/readme%20images/chrome-test.png)
![Safari](/assets/images/readme%20images/safari-test.png)

## Deployment
The following Depoloyment stages were taken. When working on my project I would have to stage regular commits in Gitpod.

* `git add .` - Adds saved files to Git's staging area
* `git commit -m ""` - Commits the saved files to the local repository
* `git push` - Pushes the commits

After pushing the commits, it is imperitive to deploy the site, and make it live. To do this:-

* Open Github and find the repository we are looking to deploy.
* Click on settings on the right hand side of the repository.
* Under code and automation, find the option pages.
* Under Build and Depoloyment -Source- select deploy from branch.
* The site is now live.

## Issues found

I feel that Issues arose from the sizing of elements. As soon as the pixel width decreased, the issues appeared which has led to a lot of specifically targeted media queries. I feel in the future, it is important for me to utilise the height and width properties well, to avoid so many media queries in the future.

Despite having a lot of media queries for specific elements, I like how the project comes together and it is responsive to the majority of devices.

I felt that I wasn’t as clued up about flex-box as I felt I was and that contributed to several issues, such as columning and alignment and getting my layout the way I wanted to. For future projects, I will apply this in a much better way.

My desire to have an accessible navigation bar on the left hand side of the page caused me some problems. My understanding is that it's best practice not to use a float value, however as mentioned, the lack of flex-box knowledge led me to use this method. Future projects will incorporate this, as mentioned

## Future scope

Future development of the site revolves around usability. 
* I would like to incorporate a drop down navigation menu when the pixel size becomes smaller. 
* As the page view changes, a link to the top of the page would prove useful. 
* I’d like to include an aside that could allow for a live twitter feed for upcoming community outdoor events. This could also be used for Instagram posts, maybe with a relevant hashtag that could link to the site.
* An about us section with images and bios about group founders and their personal inspirations. 
* Links to more services to help those with accessibility issues.

## Useful Sources & Thanks

Whilst I used a lot of advice from the current curriculum at code institute useful websites include:-

* [W3Schools](https://www.w3schools.com/default.asp)
* Slack - Code Institute community
* [Stack overflow](https://stackoverflow.com/)
* Overall google searches.

 
I’d like to give thanks to my mentor Lauren-Nicole, who has been able to show me what best practises I should take when developing a front-end website.

Also the Code institute slack community who have assisted in any issues that have cropped up throughout my design.

The opening screenshot was used from the following website:- [Am I responsive](https://ui.dev/amiresponsive)

Thank you for taking the time to go through my website, and I am open to recommendations and welcome critique. 

