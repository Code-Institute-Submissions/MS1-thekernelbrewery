# [MS1-thekernelbrewery](https://p0shjosh.github.io/MS1-thekernelbrewery/)

- [Introduction](#introduction)
- [UX](#ux)
  * [The Design](#the-design)
  * [Wireframes](#wireframes)
    + [Index](#-index---assets-wireframes-indexpng-)
    + [Beers](#-beers---assets-wireframes-beerspng-)
    + [Taproom](#-taproom---assets-wireframes-taproompng-)
    + [Education/Events](#-education-events---assets-wireframes-eventspng-)
    + [Contact](#-contact---assets-wireframes-contactpng-)
- [User-stories](#user-stories)
- [Features](#features)
  * [Existing Features](#--existing-features--)
    + [Index.html](#-indexhtml-)
    + [Beers.html](#-beershtml-)
    + [Taproom.html](#-taproomhtml-)
    + [Events.html](#-eventshtml-)
    + [Contact.html](#-contacthtml-)
  * [Future Features](#--future-features--)
  * [Technologies Used](#--technologies-used--)
- [Testing](#testing)
- [Credits](#credits)
  * [Content](#content)
  * [Inspiration](#inspiration)
  * [Acknowledgements](#acknowledgements)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>

# Introduction

The Kernel Brewery is one of the longest standing craft breweries in London, and unintentionally lead to the blossoming of the Bermondsey Beer Mile. 

Unlike other breweries, who use fantastic designs and names to add to the appeal of their beers, The Kernel Brewery opted to allow their beer to speak for itself, and not focus on branding, which in turn has to lead to iconic branding in the UK craft beer scene of the simple brown wrapper. Their website however does not share that status, and so the aim of this task was to update their website to reflect a modern website, whilst still focusing on the product and not branding. 

This project is currently deployed to [Github Pages](https://pages.github.com) and is available to view at the following link: https://p0shjosh.github.io/MS1-thekernelbrewery/

# UX

## The Design

As mentioned, The Kernel Brewery does not have an emphasis on branding in the way breweries like Deya, or Beavertown, might. The only colour present in any of Kernel's branding is the iconic brown labels (as shown in all product images). According to the owner, Evan O'Riodain, the label is "just supposed to say that this is what this beer is. A lot of what we do is - we keep quiet so the beer speaks louder." - quote taken from [Claire Bullen, 2018](https://www.goodbeerhunting.com/blog/2017/12/28/in-bermondsey-a-steady-heartbeat-the-kernel-in-london-england). This meant this choice had to carry across into my design choices for the website design, and so the only colours used are:

- white 
- black 
- grey '155,155,155'

The idea behind this choice is that the only other colour present on the site is the brown of the packaging, and so when the user is on a page with the images, they are drawn to that iconic packaging, and their attention is not divided amongst other images and logos. 

In terms of effects used, again, they also had to be simple, and not too distracting for the user. It allows for some interaction for the user, but not distracting from the content at all. The only image effect used across the site is credited to [Mike Young](https://miketricking.github.io/bootstrap-image-hover/) and specifically is Hover Effect 13. This effect was selected due to the fact that it has no extra transitions or effects beyond the text fading in; thus allowing for that interaction without going overboard. The effects are used only on each of the product images to display the information about each beer. Being used elsewhere would distract from the content. 

## Wireframes

I used Adobe XD to create the wireframes initially, and each page can be viewed in /assets/wireframes. The design for the full resolution version can be viewed through the title links below, mobile designs are present in the folder. The change from initial design to end product will be discussed below.

One feature that is present across all the wireframes but not on the final product was the placement of the footer. Initially, it was planned to have the footer also be in a fixed position, so, even with scrolling the footer be present - thus why on the wireframes it is sometimes across the centre of the image, which was meant to represent the bottom of the browser window on the pages loading. That idea was scrapped by the time the footer came to be initially implemented onto the site, so is not present in any commits. 

### [Index](/assets/Wireframes/index.png)
The Hero Image ending up becoming a hero video on larger resolution screens, that was also visible beneath the header. The placeholder text was also removed. In the earliest commits, placeholder text is visible, however this was removed due to seeming unnecessary and distracting from the content. The video remained however, as it seemed an appropriate and enticing entry to the site. The view of the beer being poured intending to cause the user to actually desire a beer, and entice them to visit the shop page. 

### [Beers](/assets/Wireframes/beers.png)
The initial wireframe shows the sections being broken down into Core, Seasonal, Specials. This ended up becoming Pale & Hoppy, Dark, and Sours & Saisons. As I read more about The Kernel Brewery, it became clear that the original titles would not fit, rather breaking their beers down into styles and explaining how each one changes with each release. 

### [Taproom](/assets/Wireframes/taproom.png)
The page was simply meant to inform the user of what beers are pouring in the taproom, when the taproom is open, and where it was located. The design was simple, and continued over into the end product. 

### [Education/Events](/assets/Wireframes/events.png)
In the initial design, this page was meant to inform the user about the process behind brewing and how The Kernel makes each of their beers. However, it was decided what was more effective was to make this a dedicated events page to list all the festivals the brewery would be attending throughout the year. This decision was made due to the fact that information on the brewing process is available in many books and on many websites, and The Kernel have not reinvented the wheel so to speak, so informing users on which festivals the beers will be poured at, and in the future, informing on events being held at the brewery/taproom too, felt more appropriate. 

### [Contact](/assets/Wireframes/contact.png)
The initial wireframes shown that the opening hours were meant to feature here too, and be positioned beneath the "address box", with an image to fill the whitespace on the right-hand side of the screen. Ultimately, the need for an image wasn't required, and I decided that the opening hours already featuring twice on the site was sufficient, and so having a "Go Direct" box, as well as the "address box" was more ideal - it also sufficed to having a box on either side of the interactable form. 

# User-stories
- As a site visitor, I want to see the latest beers each time I come back to the site, so I visit more often.
    - [Achieved through the "Latest Releases" section on the homepage.](/assets/images/userstories/Latestrelease.png)
- As a site visitor, I want to be able to get back to the home page quickly and easily, so I don’t get lost navigating and so the site works like every other site in the world.  
    - [Achieved through clicking on the site logo/name in the top left corner of the header, or in the centre on mobile browswers. Logo opacity fades to indicate this.](/assets/images/userstories/returnhome.png)

- As a brewer, I want to be able to send a message to the brewers to suggest a collaboration. 
    - [Achieved on the contact.html page, by selecting "Brewer" on the dropdown selection.](/assets/images/userstories/brewercontact.png)

- As a distributor, I want to be able to send a message to the brewery to discuss supplying beers. 

- As a store owner, I want to be able to contact the brewery to have their beers direct. 
    - [Achieved both on the contact.html page, by selecting "Supplier" on the dropdown selection.](/assets/images/userstories/brewercontact.png)

- As a consumer, I want to be able to message the brewery if I have a problem with their beers. 
    - [Achieved on the contact.html page, by selecting "Consumer" on the dropdown selection.](/assets/images/userstories/brewercontact.png)

- As a consumer, I want to be able to easily and quickly see the address and opening times, so that I can plan a visit accordingly. 
    - [Achieved through the google maps link on the taproom.html page, and the opening times](/assets/images/userstories/taproom.png)
    - [Achieved through the opening hours listed on index.html](/assets/images/userstories/indexhours.png)

- As a consumer, I want to be able to know what is available in the taproom, so that I can decide whether to plan a visit. 
    - [Achieved through the Taplist on taproom.html.](/assets/images/userstories/taplist.png)

- As a consumer, I want to be able to purchase beers directly from the brewery, for delivery to my home. 
    - [Achieved through an external link to The Kernel's shopify page, included on every product card on beers.html](/assets/images/userstories/purchaselink.png)

-  As a consumer, I want to know the differences between each beer, so I know which I want to buy. 
    - [Achieved through the descriptions listed in each card on beers.html](/assets/images/userstories/differentbeers.png)

- As a consumer, I want to understand why some Kernel Beers share the same name and what differentiates them. 
    - [Achieved through explanations on the beers.html page.](/assets/images/userstories/differentbeers.png)

- As a site visitor, I want to be able to clearly find the social media links, so that I can view the social presence, and check beer ratings.  
    - [Achieved through clear social media links in the footer, available on every page.](/assets/images/userstories/footer.png)

- As a consumer, I want to know which events are local to me, where I can drink the breweries beers. 
    - [Achieved through the events page, with external links to purchase tickets.](/assets/images/userstories/events.png)

# Features

## **Existing Features**

### *Index.html*
- [Navbar](assets/images/features/navbar.png)
    - Far left features the logo of the brewery which also acts as a return to home button. 
    - Links to other pages all pushed to right hand side. 
    - [Change in colour to show which page is currently active.](assets/images/features/navbaractive.png) Demonstrated on beers.html.
    - [Mobile version shows bar icon rather than full list of other pages.](assets/images/features/navbarmobile.png)
        - [Activating toggle icon through interaction does reveal the list.](assets/images/features/navbarmobile2.png)
- [Latest Releases](assets/images/features/releases.png)
    - Shows the 3 latest beers released by the brewery.
    - Hover, or click on smaller resolution screens, displays information about the current iteration of the beer.
- [Opening Hours](assets/images/features/hours.png)
    - Lists the opening hours of the taproom, available on the homepage for quick access.
- [Footer](assets/images/features/footers.png)
    - On the left side, an interactable link to the contact page.
    - Centre features the two societies the brewery is a member of, with external links to their respective pages. 
    - Right side includes external social media links to the breweries facebook, twitter, instagram, and untappd pages.
- [Hero Video](assets/images/features/herovideo.png)
    - On larger resolutions, the homepage loads with a large video playing across the page, to draw the user in and demonstrate what the website is clearly about; beer.
- [Hero Image](assets/images/features/heroimage.png)
    - For smaller, and mobile, resolutions, an image loads, which is taken from the inside of the brewery, and still demonstrates clearly what the website is about. 
### *Beers.html*
- [Beer Information](assets/images/features/beers.png)
    - Cards used were [Bootstrap Card Components](https://getbootstrap.com/docs/4.0/components/card/)
    - Each card features an image of the appropriate beer. 
    - The descriptions explain to the user what is distinct about that style. 
    - Each [button](https://getbootstrap.com/docs/4.0/components/buttons/) leads to the Brewery's already existing external shop page, allowing the user to purchase. 
- [Accordion](assets/images/features/dropdown.png)
    - At smaller resolutions, the [Bootstrap Accordion Component](https://mdbootstrap.com/docs/jquery/javascript/accordion/) organises all the cards within collapsible sections.
    - [Toggled Accordion](assets/images/features/mobiledropdown.png) shows that as one section is active, the others minimise, to keep the users scrolling to a minimum.
### *Taproom.html*
- [Taplist](assets/images/features/taplist.png) 
    - Table displaying what is currently pouring in the taproom, features all information the user should need about the offerings.
- [Map](assets/images/features/map.png)
    - Interactable google maps api allowing the user to get directions to the brewery. Address also features.
- [Opening Hours](assets/images/features/taphours.png)
    - Repeated table displaying the hours the taproom is open for. 
### *Events.html*
- [Timeline](assets/images/userstories/events.png)
    - [Bootstrap Timeline component](https://www.w3schools.com/howto/howto_css_timeline.asp) which lists for the user the events the brewery will be attending that year, with the date and address of the venue. 
    - Also features a [button](https://getbootstrap.com/docs/4.0/components/buttons/) which opens an external link to the event's ticket page. 
### *Contact.html* 
- [Contact](assets/images/features/contact.png)
    - The left side lists the addresses of both the brewery and the taproom.
    - The right side features the phone number and email allowing the user to get in touch directly.
    - The main feature, centrally, is an interactable form for the user to enter all the details in and submit a message to the brewery. 
    - [The Selection Menu](assets/images/features/contactdrop.png) of the form reveals a dropdown menu to categorise their menu for the site owner. 
    - Code for the contact form was adapted from this [Vintage Inspired Contact Form](https://codepen.io/dfitzy/pen/VepqMq) 

## **Future Features**
- *Beers.html*
    - [Untappd Integration](assets/images/features/future/untappdmenu.png), on the untappd website and app to list the live taplist of the taproom.
    - [Add the untappd menu to own site](assets/images/features/future/brewdogfull.png) to replace the current taplist, featuring the same categories already listed, but with improved styling, and cross-site compatibility. 
    - [This will also add improved responsiveness](assets/images/features/future/brewdogmobile.png) for smaller resolutions, preventing the need for x-axis scrolling, which appears unavoidable in the current state.
    - This has not presently been added due to the fact that I myself do not have access to an untappd business account, so could not prepare an untappd menu to be used on the site.

- *Contact.html*
    - Whilst the form currently works, in the sense that it requires all sections to be filled, the data currently goes nowhere. With improved personal abilities, ensure that data is actually usable by the site owner.

## **Technologies Used**

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - Semantic markup language as the shell of the site.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - Cascading Style Sheets as the design of the site.

- [Font Awesome 5](https://fontawesome.com)
    - Used for all social media links, and bars featured in the header. 

- [Bootstrap 4.5](https://getbootstrap.com)
    - Used to provide layout for elements, such as navbar and the timeline, as well as styling such as the timeline and hover effects. 

- [Google Fonts](https://fonts.google.com)
    - Fonts used; "Oswald, Jost, Roboto"

# Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

# Credits

## Content
- The text for each product was copied from their respective product page on [The Kernel Brewery's Store](https://store.thekernelbrewery.com/collections/all) 

- The images for each product were copied from their respective product pages on [The Kernel Brewery's Store](https://store.thekernelbrewery.com/collections/all) 

- The video used in the herovideo section was copied from [Coverr](https://coverr.co/videos/glass-of-beer-4JkBvtunS4)

- The image used in the heroimage section on smaller resolution screens was taken from [Goodbeerhunting](https://www.goodbeerhunting.com/blog/2017/12/28/in-bermondsey-a-steady-heartbeat-the-kernel-in-london-england)

- The Dog photo on index.html was taken from [The Kernel Brewery's Instagram](https://www.instagram.com/thekernelbrewery/)

- The hover effect on the beers on index.html was taken from [Mike Young](https://miketricking.github.io/bootstrap-image-hover/)

- The contact from was adapted from [this Vintage Inspired form](https://codepen.io/dfitzy/pen/VepqMq) created by [David Fitas/@dfitzy](https://codepen.io/dfitzy)

- The timeline was adapted from the [W3schools timeline tutorial](https://www.w3schools.com/howto/howto_css_timeline.asp)

- The images used to show the future implementation of untappd integration were taken from [Brewdog Liverpool](https://www.brewdog.com/bars/uk/brewdog-liverpool)

## Inspiration

Inspiration for this project and its design came primarily from -
- [The Kernel Brewery](https://www.thekernelbrewery.com)
- [Deya Brewing](https://deyabrewing.com)
- [The Veil Brewing Co](https://www.theveilbrewing.com)
- [Origin Coffee](https://www.origincoffee.co.uk)

## Acknowledgements 

- To [Austin](https://github.com/Austin-Ray), for improving my commits, your help, and testing everything. 

- To [Guilherme](https://github.com/guilhermegarcz/), for answering more stupid questions than you thought possible. 

- To [Luke](https://github.com/LukeParlin), for helping with testing the site and your advice. 

- To [Precious](https://github.com/precious-ijege), my mentor for this, for all your advice and guidance in getting this project done. 