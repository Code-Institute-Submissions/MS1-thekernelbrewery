# MS1-thekernelbrewery

The Kernel Brewery is one of the long standing craft breweries in London, and unintentionally lead to the blossoming of the Bermondsey Beer Mile. 

Unlike other breweries, who use fantastic designs and names to add to the appeal of their beers, The Kernel Brewery opted to allow their beer to speak for itself, and not focus on branding, which in turn has to lead to iconic branding in the UK craft beer scene of the simple brown wrapper. Their website however does not share that status, and so the aim of this task was to update their website to reflect a modern website, whilst still focusing on the product and not branding. 
 
## UX

# The Design

As mentioned, The Kernel Brewery does not have an emphasis on branding in the way breweries like Deya, or Beavertown, might. Instead, the only colours in their branding is brown for the background, and black for the text. I opted to keep to this simplicity on the website design, and so the only colours used are:

- white 
- black 
- grey '155,155,155'

In terms of effects used, again, they had to be simple, and not too distracting for the user. It allows for some interaction for the user, but not distracting from the content at all. The only image effect used across the site is taken from: https://miketricking.github.io/bootstrap-image-hover/ and specifically is Hover Effect 13. This effect was selected due to the fact that it has no extra transitions or effects beyond the text fading in; thus allowing for that interaction without going overboard. The effects are used only on each of the product images to display the information about each beer. Being used elsewhere would distract from the content. 

## Wireframes

I used Adobe XD to create the wireframes initially, and each page can be viewed in /assets/wireframes. The change from initial design to end product will be discussed below.

# Index 
The Hero Image ending up becoming a hero video on larger resolution screens, that was also visible beneath the header. The placeholder text was also removed. In the earliest commits, placeholder text is visible, however this was removed due to seeming unnecessary and distracting from the content. The video remained however, as it seemed an appropriate and enticing entry to the site. The view of the beer being poured intending to cause the user to actually desire a beer, and entice them to visit the shop page. 

# Beers
The initial wireframe shows the sections being broken down into Core, Seasonal, Specials. This ended up becoming Pale & Hoppy, Dark, and Sours & Saisons. As I read more about The Kernel Brewery, it became clear that the original titles would not fit, rather breaking their beers down into styles and explaining how each one changes with each release. 

# Taproom 
The page was simply meant to inform the user of what beers are pouring in the taproom, when the taproom is open, and where it was located. The design was simple, and continued over into the end product. 

# Education/Events
In the initial design, this page was meant to inform the user about the process behind brewing and how The Kernel makes each of their beers. However, it was decided what was more effective was to make this a dedicated events page to list all the festivals the brewery would be attending throughout the year. This decision was made due to the fact that information on the brewing process is available in many books and on many websites, and The Kernel have not reinvented the wheel so to speak, so informing users on which festivals the beers will be poured at, and in the future, informing on events being held at the brewery/taproom too, felt more appropriate. 

# Contact 
*to be added* 

## User-stories
- As a site visitor, I want to see the latest beers each time I come back to the site, so I visit more often.
- Achieved through the "Latest Releases" section on the homepage. 

- As a site visitor, I want to be able to get back to the home page quickly and easily, so I don’t get lost navigating and so the site works like every other site in the world.  
- Achieved through clicking on the site logo/name in the top left corner of the header, or in the centre on mobile browswers. Logo opacity fades to indicate this. 

- As a brewer, I want to be able to send a message to the brewers to suggest a collaboration. 
- *to be added* 

- As a distributor, I want to be able to send a message to the brewery to discuss supplying beers. 
As a store owner, I want to be able to contact the brewery to have their beers direct. 
- *to be added*

- As a consumer, I want to be able to easily and quickly see the address and opening times, so that I can plan a visit accordingly. 
- Achieved through the google maps link on the taproom.html page, and the opening times available on both index.html and taproom.html

- As a consumer, I want to be able to know what is available in the taproom, so that I can decide whether to plan a visit. 
- Achieved through the Taplist on taproom.html.

- As a consumer, I want to be able to purchase beers directly from the brewery, for delivery to my home. 
- Achieved through an external link to The Kernel's shopify page, included in the header. 

-  As a consumer, I want to know the differences between each beer, so I know which I want to buy. 
- Achieved through reading the beers.html page. 

- As a consumer, I want to understand why some Kernel Beers share the same name and what differentiates them. 
- Achieved through explanations on the beers.html page. 

- As a site visitor, I want to be able to clearly find the social media links, so that I can view the social presence, and check beer ratings.  
- Achieved through clear social media links in the footer, available on every page.

- As a consumer, I want to know which events are local to me, where I can drink the breweries beers. 
- Achieved through the events page, with external links to purchase tickets. 


## Features

### Existing Features
- 
### Features Left to Implement
- 

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- Semantic markup language as the shell of the site.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- Cascading Style Sheets as the design of the site.

- [jQuery](https://jquery.com)
- Used for interactive effects, such as selecting the bars on the navbar. 

- [Font Awesome 5](https://fontawesome.com)
- Used for all social media links, and bars featured in the header. 

- [Bootstrap 4.5](https://getbootstrap.com)
- Used to provide layout for elements, such as navbar and the timeline, as well as styling such as the timeline and hover effects. 

- [Google Fonts](https://fonts.google.com)
- Fonts used; "Oswald, Jost, Roboto"

## Testing

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

## Deployment

This project is currently deployed to [Github Page](https://pages.github.com) and is available to view at the following link: https://p0shjosh.github.io/MS1-thekernelbrewery/index.html

## Credits

### Content
- The text for each product was copied from their respective product page on [The Kernel Brewery's Store](https://store.thekernelbrewery.com/collections/all) 

- The images for each product were copied from their respective product pages on [The Kernel Brewery's Store](https://store.thekernelbrewery.com/collections/all) 

- The video used in the herovideo section was copied from [Coverr](https://coverr.co/videos/glass-of-beer-4JkBvtunS4)

- The image used in the heroimage section on smaller resolution screens was taken from [Goodbeerhunting](https://www.goodbeerhunting.com/blog/2017/12/28/in-bermondsey-a-steady-heartbeat-the-kernel-in-london-england)

- The Dog photo on index.html was taken from [The Kernel Brewery's Instagram](https://www.instagram.com/thekernelbrewery/)

### Inspiration

Inspiration for this project and its design came from -
- [The Kernel Brewery](https://www.thekernelbrewery.com)
- [Deya Brewing](https://deyabrewing.com)
- [The Veil Brewing Co](https://www.theveilbrewing.com)
- [Origin Coffee](https://www.origincoffee.co.uk)

### Acknowledgements 

- To Steven, for all your help in checking and testing my site for me. 
    - https://github.com/steventomlinson

- To Guilherme, for answering more stupid questions than you thought possible. 
    - https://github.com/guilhermegarcz/ 

- To Precious, my mentor for this, for all your advice and guidance in getting this project done. 
    - https://github.com/precious-ijege