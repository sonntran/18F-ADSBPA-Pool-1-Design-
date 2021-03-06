#ADS RFQ Pool One Design
Prototype URL: [http://agilebpa.forumone.com](http://agilebpa.forumone.com).

Agile Management Tool: [Trello](https://trello.com/b/nCt1b9Fg/18f-agile-bpa)

This tool tracked progress on the prototype and includes a timestamped chronological listing of how the prototypes was designed and developed by out team. All documentation within Trello is also in the Documentation section in GitHub.

## Description

dCARE is a tool that enables physicians, pharmacists, nurses, patients and care providers to understand the types of contraindications from taking two or more mental health drugs at the same time. The dCARE tool is specifically designed to help those who are taking or prescribing pharmaceuticals for mental health issues (antidepressants and psychostimulants/nootropics) to understand if there are potentially adverse side effects from specific combinations of medicines.

dCARE includes the ability to show contradictors for several medications at the same time. It is based on official FDA data, and reduces the research time substantially. You can track our progress on the development of the dCare tool on our [Trello board.](https://trello.com/b/nCt1b9Fg/18f-agile-bpa)

## Approach - Design Pool 

###Vision, Planning and Preparation
Before starting, Forum One designated a [Product Owner](https://playbook.cio.gov/#play6) to play the role of client, while a [design team](https://github.com/forumone/18F#team-and-labor-categories---design-pool) met to internally kick off the project. During the formal kick off meeting with the Product Owner, we developed a [vision](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/ProductVisionScenariosPersonas.md) for the prototype and held a requirements gathering workshop.

###Human-Centered Design
As Forum One sought to build a tool that not only met the criteria of the Product Owner, but also the needs of end users, we employed various human-centered design techniques. We started by taking a page from the [Digital Services Playbook](https://playbook.cio.gov/#play1) on understanding what people need. During the first few sprints, our design team began researching the needs of potential end users, developing [personas, scenarios, and use cases](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/ProductVisionScenariosPersonas.md). While we interviewed potential users, we quickly relayed the information to the design team, who, alongside the designated Product Owner, worked to create a backlog of activities that would shape the prototype.

###Iterating on Design
Our User Research Lead shared of the initial research findings with the Product Owner, and began wireframing possible solutions for the tools. Meanwhile, our visual designer worked on design comps to give a graphic represenation of the tool in action. Using a combination of [whiteboards](https://trello.com/c/olRRtiuG/14-design-sketching-requirements), [UXPin](https://trello.com/c/ZWks6dJ8/5-design-wireframing) and [photoshop](https://trello.com/c/DabuKFea/26-design-create-data-viewer-mockups), the team delivered on potential solutions that reconciled the product owner vision with the user research that had been conducted to deliver on an [intuitive, easy-to-use tool](https://playbook.cio.gov/#play3). The tool is meant to  allow users to search adverse effects by drug [quickly](https://trello-attachments.s3.amazonaws.com/55915a5a8b760d497bdb8351/2550x3300/ed9e82115da008aaf198a9166dc46167/dCare_Flow.png), and even compare effects for different drug combinations. By Sprint 4, the team was collecting usability testing feedback about the wireframes and design comps. Usability testing continued throughout the project life, from face-to-face prototype testing to [online surveys](https://www.surveymonkey.com/r/3MTG8JK), with the feedback guiding the aesthetic and technical changes to the prototype. By keeping our [team lean and on a sprint schedule](https://playbook.cio.gov/#play4) that allowed [frequent communication and collaboration](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/SprintPlanningandReviewNotes.md) including sprint planning, reviews, retrospectives and standups.

###Designing for Usability
Instead of depending on style guides built from scratch, our design team applied concepts from Google's [Material Design](https://www.google.com/design/spec/material-design/introduction.html) standards, making use of grid-based layouts, responsive animations and transitions, padding, and depth effects such as lighting and shadows. The prototype is fully responsive, allowing users to view data across devices.

###Using Open-source Technologies
A large component of our ability to stay lean and develop fast came from the use of [open-soruce technologies](https://playbook.cio.gov/#play8). Our team developed the prototype on GitHub, using modern stack of tools that include SASS, Angular, D3, Jenkins, Capistrano, Sails, Lodash, jQuery, Grunt, Bower, and NPM. 


##Design Criteria - Pool 1
| #  | Criteria | Evidence |
|----|----------|----------|
| 1  | Assigned one leader, gave that person authority and responsibility, and held that person accountable for the quality of the prototype submitted | [link](https://github.com/forumone/18F#team-and-labor-categories---design-pool) |
| 2  | Assembled a multidisciplinary and collaborative team that includes at a minimum of three of the labor categories limited to the Design Pool labor categories to develop the prototype as quoted in Attachment C | [link](https://github.com/forumone/18F#team-and-labor-categories---design-pool) |
| 3  | Understand what people need, by including people in the prototype design process | [link](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/ProductVisionScenariosPersonas.md) |
| 4  | Used at least three “human-centered design” techniques or tools | [link](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/ProductVisionScenariosPersonas.md) |
| 5  | Created or used a design style guide and/or a pattern library |  Forum One used Google's Material Design components. [link](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/TechnicalSpecifications.md#design-style-guide-or-pattern-library) |
| 6  | Used at least three modern and open source frontend or client side web technologies | [link](http://agilebpa.forumone.com/about/#/) Among others, client side technologies include: D3, Angular, SASS, jQuery |
| 7  | Performed usability tests with people | [Trello link](https://trello.com/c/P3M8k6Ag/29-user-research-usability-testing-wireframes), [Survey link](https://www.surveymonkey.com/r/3MTG8JK), [Additional evidence](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/tree/master/documentation)|
| 8  | Used an iterative approach, where feedback informed subsequent work or versions of the prototype | [Trello Board](https://trello.com/b/nCt1b9Fg/18f-agile-bpa), [Sprint Reviews/Retrospectives] (https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/documentation/SprintPlanningandReviewNotes.md) |
| 9  | Created a prototype that works on multiple devices and presents a responsive design | [link](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/tree/master/documentation/Prototype%20Screenshots%20%28responsive%29) |
| 10 | Provided sufficient documentation to install and run their prototype on another machine | [link](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/README.md) |
| 11 | Prototype and underlying platforms used to create and run the prototype are openly licensed and free of charge | [link](https://github.com/forumone/18F-ADSBPA-Pool-1-Design-/blob/master/LICENSE.md) |

## Team and Labor Categories - Design Pool
| Role  | Bio | Responsibility | LOE |
|----|----------|----------|----|
| Product Manager - M.C. Franzini | M.C. Franzini is a senior project officer at Forum One, where he leads strategy and web development projects for clients in government agencies and nonprofits. Recent clients with whom he has worked on large-scale Drupal projects include the Consumer Financial Protection Bureau, USDA’s Foreign Agricultural Service, USDA’s National Institute for Food and Agriculture, and the U.S. Department of Health’s Office of the National Coordinator for Health IT. He brings an enthusiasm for online community and collaboration, user experience and design, and building innovative web sites to help clients increase their impact. He holds an master’s in international business from the University of Edinburgh and a master’s in political management from the George Washington University. He has worked in the private, government, nonprofit, and education sectors. | M.C. Franzini has authority and responsibility over the quality of the submitted prototype. | 18 hours |
| Interaction Designer/User Research Lead - Matt Humphrey | Matt Humphrey is the Manager of User Experience Design at Forum One. He works with clients to develop an optimal user experience that balances the organization’s mission with the needs of its target users. Matt routinely combines his background in web media and instructional design and has expertise in audience research and analysis, usability testing, content strategy, wireframe development, prototyping, graphic design, and CMS development. Matt brings a broad range of web design and development experience to Forum One. He was the curriculum and technology manager at the Community Technology Centers' Network (CTCNet). At CTCNet, he oversaw the development and design of the organization's websites and managed a curriculum development project that addressed youth civic engagement issues. Matt has a master of education in instructional design and development from George Mason University and a bachelor of science in information technology and web media from Juniata College. | As interaction designer and user research lead, Matt oversees all stages of site design, including audience analysis, usability testing, front-end development, graphical creation, and visual design management. | 18 hours |
| Visual Designer - Lisa Drobek | Lisa Drobek is a Senior User Experience Designer at Forum One, where she is responsible for creating the content strategy and information architecture that extends a client’s brand to its website or mobile app. She has over ten years of experience in visual design and may also be creating all interaction and visual design aspects that support a client’s project as well. Prior to joining Forum One, Lisa was a Senior Interaction Designer at Capital One where she collaborated with project managers and developers to create functional user flows and visual designs for mobile and web applications. She also has significant experience designing content websites. Lisa earned her bachelor’s from Penn State University and her master’s in Publications Design from University of Baltimore. Her experience in publishing has driven her to advocate for digital-first content strategies that include more detailed storytelling through incorporating interactive data and long-form content on the web. | As visual designer on this project, Lisa applies her extensive knowledge of design principles and web strategy best practices in order to engage each target audience, create a high-impact user interface, and generate an optimal end-user experience. | 16 hours |
| Writer/Content Designer/Content Strategist - Mike Shoag | Michael takes a content-first approach to complex strategy and development projects. He provides a full range of content strategy, including development of communication plans, mapping goals and user journeys, organizational positioning, and messaging architecture.  Before joining Forum One, he worked at Development InfoStructure (Devis) and Interactive Applications Group (iapps), leading teams to develop and implement innovative technology solutions. He managed a team of 50 staff who trained and supported over 4,000 people in 80 countries for the USAID. He is a Certified Project Management Professional (PMP). He also provides pro-bono consulting for several small nonprofits. Michael earned a bachelor’s degree in politics, philosophy and economics at Claremont McKenna College and a master of public policy from Harvard University’s Kennedy School of Government. | Charged with content strategy, Mike has worked closely with the UX Lead and Product Owner to ensure that the Product Owner's vision was clearly communicated, while providing clear and useful context for end users who visited the dCARE site. | 12 hours |
| Frontend Developer - William Hurley | William Hurley is Manager, Technical Development for Forum One, where he is responsible for delivering smart technical solutions and managing a team of developers. His skills combine technical web development and knowledge of organizational system design, and he has been developing on the web since 1997 using PHP, Java, Adobe Flex, JavaScript, and ColdFusion. William also has extensive knowledge of XHTML/HTML, CSS and XML, and related technologies. Using Agile principles, William has led the technical development for the Educational Testing Services, EnergyStar, the Environmental Protection Agency, Robert Wood Johnson Foundation, and the World Bank. | William is responsible for developing the prototype using open source technologies. William worked closely with the project team to develop the tool and was instrumental in choosing the technology for the prototype.  | 32 hours |
	
## Installing project

The dCARE project is built using SailsJS, a real-time NodeJS framework. You can run this locally or through a Docker container.

### Running locally

In order to run the project locally you need NPM of 1.4 or higher as well as bower and sails packages installed globally. Run ```npm --version``` to check your version of NPM and then ```sudo npm update npm -g``` to upgrade as necessary. To install the packages run:

* ```sudo npm install bower -g``` to install bower
* ```sudo npm install sails -g``` to install sails

To start the site run ```sails lift``` within the root checkout. It will run the Grunt tasks and start Express so the site is available at http://localhost:1337.

To run unit tests run ```grunt test```

### Running using Docker

In order to run the project with Docker you need to install Docker for your operating system or using boot2docker for OSX or Windows. Once the project is cloned you can launch it in Docker by running: ```docker run -it -d --name 18f -p 1337:1337 -v "$PWD":/server -w /server forumone/sails /bin/sh -c "npm install && bundle install && sails lift"```

If running boot2docker run ```boot2docker ip``` to get the IP address and access it on that IP address at port 1337.

To run unit tests run ```docker run -it -d --name 18f -p 1337:1337 -v "$PWD":/server -w /server forumone/sails /bin/sh -c "npm install && bundle install && grunt test"``` and then to view the running tests you can run ```docker attach 18f```
