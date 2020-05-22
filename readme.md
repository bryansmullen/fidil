# Fidil

[View the live project here](https://bryansmullen.github.io/fidil/)

![Banner Image](pre-production/fidil_mockup_banner.jpg)

**Fidil** is an online Irish Traditional Music resource which delivers content in a bitesized, aesthetically pleasing manner which appeals to the hobbyist musician.

While there are already Irish Traditional Music resources available online, many of them take time and effort to navigate. Fidil's focus is on simplicity, so that it is instantly accessible and intuitive to even the first time user.

---

## 1. Contents

<!-- vscode-markdown-toc -->

- 1. [Contents](#Contents)
- 2. [Project Background](#ProjectBackground)
- 3. [UX Design](#UXDesign)
     - 3.1. [Goals](#Goals)
     - 3.2. [User Stories](#UserStories)
     - 3.3. [Wireframes](#Wireframes)
     - 3.4. [Color Palette](#ColorPalette)
     - 3.5. [Typography](#Typography)
     - 3.6. [Imagery](#Imagery)
     - 3.7. [Prototype](#Prototype)
     - 3.8. [Development](#Development)
- 4. [Features](#Features)
     - 4.1. [Existing Features](#ExistingFeatures)
     - 4.2. [Features Left to Implement](#FeaturesLefttoImplement)
- 5. [Technologies Used](#TechnologiesUsed)
     - 5.1. [Languages](#Languages)
     - 5.2. [Libraries](#Libraries)
     - 5.3. [Other Tools](#OtherTools)
- 6. [Testing](#Testing)
     - 6.1. [Test Process](#TestProcess)
     - 6.2. [Tests Conducted](#TestsConducted)
          - 6.2.1. [Prototype Functionality Tests](#PrototypeFunctionalityTests)
          - 6.2.2. [Prototype Design Tests](#PrototypeDesignTests)
          - 6.2.3. [Finished Project Tests](#FinishedProjectTests)
          - 6.2.4. [Validation](#Validation)
          - 6.2.5. [Modelled Device Testing](#ModelledDeviceTesting)
          - 6.2.6. [Automated Cross Browser Testing](#AutomatedCrossBrowserTesting)
          - 6.2.7. [Manual Cross Browser Testing](#ManualCrossBrowserTesting)
     - 6.3. [Test Insights](#TestInsights)
          - 6.3.1. [Prototype Functionality Insights](#PrototypeFunctionalityInsights)
          - 6.3.2. [Prototype Design Insights](#PrototypeDesignInsights)
          - 6.3.3. [Known Issues](#KnownIssues)
- 7. [Deployment](#Deployment)
     - 7.1. [Deploying on Github Pages](#DeployingonGithubPages)
     - 7.2. [Differences between deployed version and development version](#Differencesbetweendeployedversionanddevelopmentversion)
     - 7.3. [Cloning a local version](#Cloningalocalversion)
- 8. [Credits](#Credits)
     - 8.1. [Content](#Content)
     - 8.2. [Media](#Media)
     - 8.3. [Acknowledgements](#Acknowledgements)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->

## 2. Project Background

This project is being completed as part of a Full Stack Developer Diploma award. This forms the basis for the developer's first milestone project. As such it will be completed within a set of guidelines as to which technologies to use.

While the core focus of the project is to be submitted as summative assessment for the student developers course, it is also hoped that the resource itself, and the brand created for it can be developed over time into something that can be of value to the wider community.

---

## 3. UX Design

### 3.1. Goals

Design phase goals:

- Identify user profile
- Generate user stories
- Create wireframe
- Develop brand identity
- Create high fidelity prototype
- Test high fidelity prototype

The website is conceived as a resource for hobbyist musicians who want an easy to use, aesthetically pleasing resource for Irish music. The design process is to first create a user profile which is representative of the target user. The following target users are identified:

- [Music Enthusiast](https://github.com/bryansmullen/fidil/blob/master/pre-production/User%20Profiles/user_profile_james.pdf)
- [Hobbyist Musician](https://github.com/bryansmullen/fidil/blob/master/pre-production/User%20Profiles/user_profile_mark.pdf)
- [Content Creator](https://github.com/bryansmullen/fidil/blob/master/pre-production/User%20Profiles/user_profile_sarah.pdf)

### 3.2. User Stories

With the target users in mind, the following user stories are generated.

- As a music enthusiast, I want to know what different instruments are used in Irish music so that I can be more aware of what I am listening to.
- As a hobbyist musician, I want to learn detailed information about individual instruments so that I can understand their various quirks and idiosyncrasies.
- As a music enthusiast, I want to know about the different dance forms in Irish music so that I can understand why the musical forms are structured the way they are.
- As a hobbyist musician, I want to learn detailed information about each individual dance style so that I understand how to better accompany each one.
- As a music enthusiast, I want to read about Irish Music so that I can develop my own sense of Irish culture.
- As a content creator, I want to be able to contact online Irish Music platforms so that I might have my writing on the topic published.

### 3.3. Wireframes

Once the user stories are completed, [wireframes](https://xd.adobe.com/view/ddf5e229-2703-4fcc-4d65-98d347cce994-abc4/?fullscreen) are generated to form the layout of the website which allow the target user to achieve their goals. The wireframes are generated to accomodate three different screen sizes in a responsive layout:

- Macbook Pro (2019)
- iPad Pro (12.9")
- iPhone X

### 3.4. Color Palette

Next the brand is designed. This involves the creation of a [logo](https://github.com/bryansmullen/fidil/blob/master/assets/img/fidil_logo.svg), compiling of a [color palette](https://color.adobe.com/Fidil-Options-color-theme-15024567), and selection of appropriate [font choices](https://use.typekit.net/hmk0dts.css).

The colors palette chosen for the brand consist of blues and oranges. The blues represent the refreshing, reliable nature of the website delivering the content, while the orange represents the vibrant creativity inherant in Irish music.

The orange shade derives from a shade of orange found in the wood of a picture of a fiddle, and this same photo also forms the basis of the curve of the logo. The blue shades, as well as the red shade are then selected using [Adobe Color Picker](https://color.adobe.com/create) to experiment and find shades to compliment.

### 3.5. Typography

[Century gothic](https://fonts.adobe.com/fonts/century-gothic) is selected as the primary typeface for the major headings because of its modern, sleek design, as well as it's striking look in headings and logos. It is well supported across modern browsers according to [fonts.com](https://www.fonts.com/font/monotype/century-gothic/story). [Minion Pro](https://fonts.adobe.com/fonts/minion) is chosen to compliment it through the body text, and it is recommended by [bonfx.com](https://bonfx.com/fonts-that-go-with-century-gothic/) as a less serious, more friendly pairing than some of the other options available.

### 3.6. Imagery

[Shutterstock](https://www.shutterstock.com/) is used as the primary source of imagery for the website as it provides high quality images available for licensing. Licenses have been obtained for all imagery used in this project in line with their Standard License.

### 3.7. Prototype

With these decisions in place a high fidelity [prototype](https://xd.adobe.com/view/3b60cd6d-786b-40d6-638f-78cb19bc9942-4d51/) is created drawing together all strands of the design to show what the developed project will look like. Decisions such as placement of content, sizing of images, application of color and typography palettes are taken at this point. Once completed, the prototype undergoes testing to ensure that content is easily accessible to first-time users, and testing insights are documented. Once testing is completed, the development assets are exported in the form of jpg and svg files, in appropriate sizes for each device as applicable.

### 3.8. Development

Development phase goals

- Creation of index.html document
- Styling of index.html using style.css and Bootstrap 4 library
- Creation of additional html pages using common elements from index.html (header, footer etc)
- Styling of additional pages
- Initial deployment on Github Pages
- Testing of deployed website
- Final adjustments
- Submission

The development phase uses only the technologies covered in the course up until the point of Milestone Project One. These consist of HTML and CSS, extended by the Bootstrap 4 library. There is no custom Javascript or other technologies included for this release. The only exception is the use of elements within Bootstrap 4 which have pre programmed javascript/jquery behaviour, which may be utilised.

Once completed the [index.html](https://github.com/bryansmullen/fidil/blob/master/index.html) file is created taking care to copy & paste all available copy so as not to risk typographical erros, and thereafter the [style.css](https://github.com/bryansmullen/fidil/blob/master/assets/css/style.css) file is created to style the page to match the specification, using Bootstrap where appropriate.

Additional html files are created as necessary copying common elements from the index.html file such as headers and footers. Once created, the style.css file is amended to include styling for the additional pages.

Once completed the initial deployment takes place on Github Pages, at which point it is tested.

Once final adjustments are made the project is committed to and submitted.

---

## 4. Features

### 4.1. Existing Features

- Home page - allows all users to access the top level navigation of the website, by interacting with the navigation bar, or the individual content cards.
- Instruments page - allows music enthusiasts to learn basic information about different instruments, by reading each individual instrument card.
- Instrument modal - allows hobbyist musicians to learn mroe in-depth information about each instrument by activating the individual instrument modal.
- Dances page - allows music enthusiasts to learn basic information about different dances, by reading each individual dance card.
- Dance modal - allows hobbyist musicians to learn mroe in-depth information about each dance type by activating the individual dance modal.
- History page - allows music enthusiasts to read articles about Irish Music by selecting an article using the 'Read More' feature.
- Contact modal - allows content creators to get in contact with the developer by selecting one of the contact options available in the contact modal.

### 4.2. Features Left to Implement

- MIDI playback tool - Develop a MIDI player which can organise tunes into sets and play them back at desired tempo to practice to.
- History database - develop a dynamic webpage which automatically organises content in the History page into searchable categories based on topic, date, and popularity.
- Tune database - develop a system for users to submit their own tunes in a way which will be compatible with the MIDI playback tool, and which will group different settings of the same tune in a simple, elegant fashion.

---

## 5. Technologies Used

In this section, I will mention all of the languages, frameworks, libraries, and any other tools that I have used to construct this project.

### 5.1. Languages

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) is used to render the content of the website.
- [CSS3](https://www.w3.org/Style/CSS/#specs) is used to style the content of the website.

### 5.2. Libraries

- [Bootstrap 4.4](https://getbootstrap.com/) is used to aid with the layout and styling of the website, particularly mobile navigation and modals.
- [JQuery](https://jquery.com) is used to allow Bootstrap to function.

### 5.3. Other Tools

- [Adobe XD](https://www.adobe.com/ie/products/xd.html) waiss used to construct both wireframes and prototypes.
- [Adobe Photoshop](https://www.adobe.com/ie/products/photoshop.html) and [Adobe Illustrator](https://www.adobe.com/ie/products/illustrator.html) are used to create design assets.
- [Visual Studio Code](https://code.visualstudio.com/) is the main IDE used by the developer for this project.
- [Adobe Fonts](https://fonts.adobe.com/) is used to select and serve the fonts used in this project.
- [Adobe Color](https://www.adobe.com/ie/products/color.html) is used to select the color palette used in this project.
- [Git](https://git-scm.com/) is used for version control in this project. Over the course of the project a Develop branch has been added to the project to allow work to continue on the website without breaking the functioning version on the Master branch.
- [Github](https://github.com/) is used as a remote repository for the site, as well as for deployment of the final version.
- [BrowserStack](https://www.browserstack.com) is used during the testing phase to visualise how the site will render on different browsers.

---

## 6. Testing

### 6.1. Test Process

Testing is carried out at three phases to evaluate the prototypes functionality, the intuitiveness of the design, and finally verify the functionality of the final product.

### 6.2. Tests Conducted

#### 6.2.1. Prototype Functionality Tests

The function of these tests is to verify all links in the prototype lead to the expected locations, so that it is possible to proceed with testing the layout with a new user.

[Prototype functionality tests](https://we.tl/t-lNyKGpBiHT)

#### 6.2.2. Prototype Design Tests

The function of these tests is to ensure the design choices have resulted in an intuitive layout that facilitates first time learning and ease of locating the desired information.

The following tasks were set to the user to ensure intuitive layout:

- Find the name of a common dance style listed on the page.
- Locate information about the Bodhran on the site.
- Find the name of one important collector in irish music history.
- From the same section as the previous task, find where it states what genres irish music has had and influence on in music history.
- Find the link to get in touch with the developer through linkedin (the link will not currently click through).
- Return to the home page from any other page.

[Prototype design tests](https://we.tl/t-akHu55OIfG)

#### 6.2.3. Finished Project Tests

The function of these tests is to ensure that the finished project renders in an acceptable fashion on all intended devices. Four sets of tests were completed:

- Validation
- Modelled Device Testing
- Automated Cross Browser Testing
- Manual Browser Testing

#### 6.2.4. Validation

Further to this, all HTML and CSS in this project is validated by using the [W3C Markup Validation Service](https://validator.w3.org/) and the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).

![Valid HTML](https://uglyduck.ca/wp-content/uploads/2020/04/html5-validator-badge.svg) HTML Validated without errors on 19 May 2020

![Valid CSS](http://jigsaw.w3.org/css-validator/images/vcss)CSS Validated without errors on 19 May 2020

#### 6.2.5. Modelled Device Testing

To test the layout on multiple devices, Google Chrome DevTools is used to simulate the size of multiple devices and screen ratios. Screen responsiveness has been noted to ensure the correct screen ratio was delivered, links are tested by clicking through, images are checked to ensure they displayed correctly on all devices, and the website as a whole is checked to ensure everything renders as expected. Any faults or issues were noted in the [testing spreadsheet](https://github.com/bryansmullen/fidil/blob/master/pre-production/Fidil%20Testing%20Chart.pdf).

The following device dimensions are tested:

- Moto G4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5/SE
- iPhone 6,7,8
- iPhone 6,7,8 Plus
- iPhone X
- iPad
- iPad Pro
- Laptop 1024px
- Laptop L 1440px
- 4k -2560px

#### 6.2.6. Automated Cross Browser Testing

To test the layout on multiple browsers, [browserstack](https://www.browserstack.com) is used to screenshot how the layout will render on a number of different versions of major browsers, on the more up-to-date operating systems. These screenshots are then inspected and the results are once again documented in the[testing spreadsheet](https://github.com/bryansmullen/fidil/blob/master/pre-production/Fidil%20Testing%20Chart.pdf). The following browsers are tested:

- Mac OS Catalina Chrome 69
- Mac OS Catalina Chrome 70
- Mac OS Catalina Chrome 71
- Mac OS Catalina Firefox 61
- Mac OS Catalina Firefox 62
- Mac OS Catalina Safari 13.1
- Mac OS Mojave Opera 12.12
- Mac OS Mojave Opera 12.14
- Mac OS Mojave Opera 12.15
- Windows 8.1 Opera 12.14
- Windows 8.1 Opera 12.15
- Windows 8.1 12.16
- Windows 10 Chrome 69
- Windows 10 Chrome 70
- Windows 10 Chrome 71
- Windows 10 Edge 16
- Windows 10 Edge 17
- Windows 10 Edge 18
- Windows 10 Firefox 61
- Windows 10 Firefox 62
- Windows 10 Internet Explorer 11

Note that throughout this set of testing all Opera browser testing did not render, so these results were deemed inconclusive. Microsoft Edge and Chrome 69 produce a minor issue where blend mode did not render. Internet Explorer is unable to correctly render the website.

#### 6.2.7. Manual Cross Browser Testing

To complement the above results the website is also tested manually on up-to-date browsers available on the developer's machine. The results are once again documented in the[testing spreadsheet](https://github.com/bryansmullen/fidil/blob/master/pre-production/Fidil%20Testing%20Chart.pdf).

The following browsers are tested:

- Mac OS Catalina Opera Version 68.0.3618.125
- Mac OS Catalina Edge Version 81.0.416.77
- Mac OS Catalina Brave Version 1.8.96
- Mac OS Catalina Chrome Version 81.0.4044.138
- Mac OS Catalina Safari Firefox 76.0.1 (64-bit)
- iOS 13.3.1 iPad Pro Safari
- iOS 13.3.1 iPad Pro Chrome
- iOS 13.4.1 iPhone Safari
- Windows 10 Microsoft Edge 44.18362.387.0
- Windows 10 Google Chrome 81.0.4044.138 (Official Build) (64 Bit)

### 6.3. Test Insights

The following insights were gained from the testing process.

#### 6.3.1. Prototype Functionality Insights

- Fidil Logo will lead to home page on all pages, not possible in prototype.
- Hover and click states of all links to be consistent - light color for hover, dark color for click.
- **Read More** button should have micro interaction for hover and click states.
- Modal can be closed in multiple ways, this will be retained.
- External LinkedIn & Github links will be functioning in final developed website.
- Images require standardisation across all layouts at respective resolutions and sizes.
- Bodhran photo to be corrected on phone layout.
- Font size on modals to be reduced on phone layout.

#### 6.3.2. Prototype Design Insights

- Home link not working on web history page, this will be fixed on developed website.
- Bodhran image has once again reverted to incorrect image on phone layout. Flagged to be fixed.
- Tendancy for people to go first to header for contact link, then footer. This will be accepted to separate primary navigation from secondary.
- One user reported scrolling to be arduous in their browser, will consider adding a **back to top** button in development.

#### 6.3.3. Known Issues

The following issues have been noted from the Finished Project Tests:

- Blend modes do not function as expected on Google Chrome 69 and earlier.
- Blend modes do not function on Edge 18 and earlier.
- The website is incompatible with Internet Explorer version 11 and earlier.
- The Fidil logo becomes unusually large on iPhone Safari in landscape orientation.
- On screen sizes between Pixel 2 and iPhone X The history page modals create a collision between the longer title and the modal close button.
- Bootstrap can potentially be removed from this project and the navbar, modals, and custom breakpoints may be delivered using CSS or possible JS. Consider for next update of site.

---

## 7. Deployment

This project is deployed on Github Pages, which can be accessed at [Fidil Github Repo](https://github.com/bryansmullen/fidil) or [Fidil Deployed Version](https://bryansmullen.github.io/fidil/). The deployment is linked to the Master Branch of the repo, and will automatically update the deployment when any changes are committed to this branch of the remote repository.

### 7.1. Deploying on Github Pages

The following procedure was followed to deploy on Github Pages.

1. Navigate to the [Github Repo](https://github.com/bryansmullen/fidil)
2. Select the **Settings** tab
3. Scroll down to the **Github Pages** section
4. Under the **Source** dropdown, select **Master Branch**
5. Under **Theme** click **Change Theme** and then click the **Select Theme** button

### 7.2. Differences between deployed version and development version

A second **Develop** branch also exists in this repository to allow changes and updates to be made to this project without disturbing either the master branch or the live deployment. At the time of submission of this project, both the Master Branch and the Develop Branch are in sync.

The process for updating the project in future will be to make all changes on the Develop branch, or on additional feature branches, and only merge back to the Master Branch once a fully functional version is ready to commit.

### 7.3. Cloning a local version

To clone this project locally, complete the following steps:

1. Open a new Command Line Editor on your computer
2. Navigate to the folder you wish to create the local copy of this repo using the `cd` command. e.g. `cd my_directory`
3. Clone the remote repository using the git clone command. `git clone https://github.com/bryansmullen/fidil`
4. Open the newly created **fidil** directory in your favourite IDE.

---

## 8. Credits

### 8.1. Content

The text content from the website was copied from Wikipedia
[Home Instruments Card](https://en.wikipedia.org/wiki/Irish_traditional_music)
[Home Dances Card](https://en.wikipedia.org/wiki/Irish_traditional_music)
[Home History Card](https://en.wikipedia.org/wiki/Irish_traditional_music)
[Fiddle](https://en.wikipedia.org/wiki/Irish_fiddle)
[Uilleann Pipes](https://en.wikipedia.org/wiki/Uilleann_pipes)
[Bodhran](https://en.wikipedia.org/wiki/Bodhr%C3%A1n)
[Jigs](https://en.wikipedia.org/wiki/Jig)
[Reels](<https://en.wikipedia.org/wiki/Reel_(dance)>)
[Hornpipes](https://en.wikipedia.org/wiki/Hornpipe)
[History 1](https://en.wikipedia.org/wiki/Irish_traditional_music)
[History 2](https://en.wikipedia.org/wiki/Irish_traditional_music)

This readme file was based on content provided by [Code Institute](https://codeinstitute.net/)

Git template used from second mentor meeting (commit f70d591ab423c5d6c00373b50f65a9cf9422ddc6) onwards adapted from [Chris Beams](https://chris.beams.io/posts/git-commit/)

The svg background pattern was based on a tutorial from [webdesign.tutsplus.com](https://webdesign.tutsplus.com/tutorials/how-to-use-svg-patterns-as-backgrounds--cms-31507) and updated with a customised path.

The customisation of bootstrap navbar toggler breakpoint was adapted from a thread on [stack overflow](https://stackoverflow.com/questions/19827605/change-bootstrap-navbar-collapse-breakpoint-without-using-less)

### 8.2. Media

The photos used in this site were obtained from:

- Pre-production User Profile
  - Fence Photo by Ana Cruz on Unsplash
  - Mark Photo by ThisisEngineering RAEng on Unsplash
  - Sarah Photo by Annie Spratt on Unsplash
  - James Photo by Andrea Piacquadio from Pexels
  - User Profile Template from Bring Your Own Laptop UX/UI Design Course Files
- Content imagery licensed from [Shutterstock](https://www.shutterstock.com/) under their standard license. The images with the following ID numbers have been licensed:
  - 667984198
  - 667984201
  - 1430859554
  - 761648701
  - 219680854
  - 574147108
  - 258054788
  - 752652976

### 8.3. Acknowledgements

I received inspiration for this project from:

- [Irish Traditional Music Archive](https://www.itma.ie/)
- [The Session](https://thesession.org/tunes)
- [Online Academy of Irish Music](https://www.oaim.ie/)

I received much advice, coaching and steering towards good development practice on this project from my Code Institute mentor [Precious Ijege](https://www.linkedin.com/in/precious-ijege-908a00168/).

Special thanks to [David](https://www.linkedin.com/in/david-mullen-4b90ba91/), Gillian, and [Patricio](https://www.linkedin.com/in/pharteg/) for help in the testing stages, as well as [Carlos](https://github.com/BetaHope), Ngiap, Orla, and [Simen](https://www.linkedin.com/in/simendaehlin/) for their very helpful feedback.
