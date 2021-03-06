# Personal Portfolio Project

# Live Site Links
<b><p>Live Site: <a href="https://peaceful-lichterman-8455b7.netlify.com/">https://peaceful-lichterman-8455b7.netlify.com/</a></p></b>
<b><p>GitHub repo: <a href="https://github.com/PraveenMut/portfolio-project">https://github.com/PraveenMut/portfolio-project</a></p></b>

# Design Ethos (Purpose)

The design principles and its related ethos was inspired from a blend of sleek gradients (the current generation of design with flat UI) and "brutalist"/"raw" design from analytical websites such as Bloomberg. This unique blend juxtaposes each other in a tasteful manner which reflects my personality as a whole.

Due to the nature of the purpose, a desktop-first approach (Macbook, iPad) was in mind rather than mobile. 
 
It employs a contrasting colour palette of Blues, Pinks/Light-reds, Blacks, Whites (monochromatic) and pastille/cream whites for content boxes.

The main design focus was drawn back to the "raw" design mentality where the typography and clean visual hierarchy is centre-stage instead of complications such as excessive images which distract away from the clean UI.

However, text, progress bars were designed in the gradient/flat UI.

## Fonts Used:
<b>Roboto Slab</b> for headings and <b>Raleway</b> body were used as universal fonts.

# Design Intricacies (Process):

The design process revolved around finding specific colours, inspiration for potential websites that could be used as a basis for creating original work. As also explained below, I very much resonated with clear & bold yet fluid design. My personality is both an "analytical" yet "easy going/friendly" one and to ensure that it encapsulated those traits, the brutalist yet flat UI design was the best design aesthetic I wished to create.

Instead of images or other "complications" such as animations, I focused mainly on vivid, bold & stern headings coupled with fluid text on the body and the navigation sidebar. 

In regards to colour, <a href="https://mycolor.space/">My Color Space</a> was used to find complementary colours and contrasting colour sets.

<img src="./docs/colourspace.png">

 After much consideration, these colours were used:

<img src="./docs/selectedcolours.png">

The colours of Pastel Blue, Pink / Pastel Red were the base colours which then gold, black, white and cream for containers were used for the rest of the scheme. This provided a <b>"bold"</b> architecture while keeping the <em>smooth</em> feel. 

## Figma Screenshots:

### Moodboard
<img src="./docs/moodboard_figma.png">

### Original Conception:
<img src="./docs/original_conception.png">

### Proposed Desktop Design:
<img src="./docs/desktop_design.png">

### Mobile Wireframe
<img src="./docs/mobile_wireframe.png">

### Desktop Wireframe:
<img src="./docs/desktop_wireframe.png">

### Direct Figma Link:
<b>https://www.figma.com/file/J7yp0RZjak8kIwH8rFycun8S/Untitled?node-id=0%3A1</b>


This concludes the design considerations of the site. In summary:
- Having a bold layout through asserting and dominant typography
- Having a smooth layout with the clean navigation bar and "rounder" fonts
- A simple colour scheme
- Emphasis on typography


# Project Timeline

Similar to trello, the process of the project revolved around inspiration for design, mockups with design on Figma, mental aspects of designs, visiting beautiful, simple yet functional websites such as:

<p><a href="https://wired.com">Wired Magazine</a></p>
<p><a href="https://www.technologyreview.com/">MIT Technology Review</a></p>
<p><a href="www.bloomberg.com">Bloomberg</a></p>
<p><a href="www.stripe.com">Stripe</a></p>
<p><a href="www.nytimes.com">New York Times</a></p>
<p><a href="https://dev.to/">Dev Community (dev.to)</a></p>
<p><a href="https://1stwebdesigner.com/inspiration-brutalist-web-design/">https://1stwebdesigner.com/inspiration-brutalist-web-design/</a></p>
<p><a href="https://zero.app">Zero Banking</a></p>

After conceiving of designs, this was created in a final sketch in Figma. This was consequently approved and then the development of the website commenced with a focus on modularity rather building an entire monolith. 

Therefore, the website was built on a component-first approach. This is where components were initially developed (in a canonical navigation/drectory order) and then these components were replicated and then stitched together to create the overall webpage. The process of building these components (such as the navbar, about section, mobile nav, contact form, portfolio) are listed in the <b><a href="https://github.com/PraveenMut/portfolio-project/commits/master">GitHub commit history</a></b> and also on <b><a href="https://codepen.io/PraveenMut/">CodePen</a></b>.

Afterwards, design considerations for mobile were undertaken by ensuring that for small viewports, relevant media queries were utilised to hide the navigation and components that were not optimised for mobile were altered to display the content as best as possible despite the lack of real estate. 

# Usability Considerations
Although the site was designed originally for desktop, after much experimentation and testing, usability was deeply considered on mobile. This included for a prominent mobile navbar (through the employment of the classic hamburger menu), responsive text using dynamic fonts that resize according to the viewport and margin considerations on content boxes. In particular, the about page was <b>completely</b> revamped for mobile due to its original desktop-first nature. 

The mobile version ensured that all content boxes were displayed in columns and text was clearly legible. 

Minimal images were used to emphasis on the "vanilla" / "clean" effect. Stylistic background images were also removed for usability as it interfered with the diplaying of the content. 

In regards to the desktop, the emphasis was more towards the clear display of text and fast accessiblity of links from the navbar (socials are on the bottom). 

# Trello

<img src="./docs/trello.png" />

# Functionality / Features

Referring back to core design ethos of simplicity, fast performance (optimised SVG path images or large images stored in lossy compression while preserving detail) was the <b>primary key</b>. Thus, only a few PNGs and JPGs were used.

In regards to aesthetics, A tasteful gradient navbar, with a logo and a clean navigation was the key highlight of the page. Contrasting this vibrance is the main content displaying the "raw" design on the right with an emphasis on <b>functionality</b>. Everything that one needs is on the home page or in the navigation bar. 

# Site Map

The site follows a straight-forward "brutualist"/"raw" UX emphaising ease of use than unneeded complications as previously stated. Therefore, the site offers 4 distinct sections: Home, About, Portfolio and Contact.

The pages are as follows:

## Home
Home contains all of the main information that prospective viewers are looking for. This includes my name, who I am and skillsets. 

## About
Detailed information about myself with a description of my experiences in industry, listing interests and providing a condensed excerpt of my resume with a link to the full resume. 

## Portfolio
This page provides a clean view of all of the projects that I have completed.

## Contact
This area provides an area for prospective employers to contact me.

# Screenshots

Desktop:

<p>Selected Page (Home / Main Page):</p>
<img src="./docs/screenshot-desktop1.png" width="90%">

<p>Selected Page (Portfolio Page):</p>
<img src="./docs/screenshot-desktop2.png" width="90%">

Mobile:

<p>Selected Page illustrating top navigation bar usage (Home Page):</p>
<img src="./docs/screenshot-mobile1.png" />

<p>Selected Page illustrating bottom navigation bar usage when screen real estate is unavailable to fit the top nav bar.</p>
<img src="./docs/screenshot-mobile2.png">

Trello: see <a href="#Trello">Trello</a>

# Target Audience

The target audience of the portfolio project will be other technology professionals, employers and other individuals interested in discussing opportunities or technical topics with me. The overall goal of this portfolio project is to showcase my skills and provide an online presence.

# Tech Stack

This site uses the vanilla HTML5 & CSS3 stack to adhere to the project's specifications. The site is deployed to Netlify's PaaS with Continuous Integration from GitHub.

# Questions and Answers

## Key events in the development of the Internet

- 1962 >> Discussion of a Galatic Network
- 1966 >> APRANET draft
- 1967 >> APRANET published
- 1980 >> Ethernet Standard Introduced
- 1981 >> Computer Science Network
- 1991 >> Birth of the Good Ol' World Wide Web
- 1992 >> ISPs offer dialup in the U.S. (28.8k)
- 1993 >> Amazon is incorporated, an internet revolution is born
- 2000 >> Dot Com bubble burst
- 2003 >> Facebook founded
- 2014 >> SV Boom, VC Funding hits a record high, a "Yo!" app is valued at $1,000,000 USD
- 2016 >> Convenience boom, Almost any product can be order online. One never has to leave the house.


## The fundamentals of the Internet

At its core, the Internet is a set of interconnected networks that connect a computer with another in a mesh-based form. 

Thus, to orchestrate such a vast network where there is little order, protocols and layers need to be established.

The techniques are as follows:
- Packet Handling and Transport Handling (UDP, TCP/IP)
- The routing of traffic (DNS)
- The protocol method of transmitting client-server data in a formalised manner (HTTP, FTP)

### Packet Handling and Transport Handling
This allows for transport of data from one PC to another PC (typically client to server) to occur in a formalised manner. This is the base layer that can allow traffic to flow.

### DNS / Routing
DNS, or Domain Name System, is a decentralized directory that translates domain names from the transport layer (base layer) to IPs and then routes it to the correct server.

### HTTP / Document Handling
These allow for data from requests from URLs to occur. HTML documents can be sent through this protocol.

## Impact of the Internet to the world
The original goal of the internet was to provide the collective intelligence of many individuals across the globe. As there is no restrictions (until recently) on what knowledge could be shared, this is single handily  the most powerful innovation created by mankind. Instead of being restricted on the intelligence of what 1 individual or corporation, now anyone, anywhere, regardless of any status can access the world's knowledge in the hands of their pocket. 

Ordering a pizza? Sure! Booking a ticket? Sure! Understanding science? Don't run to the library for outdated texts, just go type it in Google. Not sure where you are and need a taxi? Easy.

One is only limited by their imagination through disruptive technology of the Internet.

Ordering a pizza? Sure! Booking a ticket? Sure! Understanding science? Don't run to the library for outdated texts, just go type it in Google. Not sure where you are and need a taxi? Easy.

One is only limited by their imagination through disruptive technology of the Internet.
