# Fidil

An Irish Music Resource

**Fidil** is an online Irish Traditional Music resource which delivers content in a bitesized, aesthetically pleasing manner which appeals to the hobbyist musician.

There are already Irish Traditional Music resources available online, however, many of them take time and effort to navigate. Fidil's focus is on simplicity, so that it is instantly accessible and intuitive to even the first time user.

---

## Preface

This is a live working document based on a recommended template. As such, some sections have not yet been filled in. They are represented as blockquotes and will be filled in in due course.

---

## Contents

1. Project Background
2. UX
   2.1. Design
   2.2. Development
3. Features
   3.1. Existing Features
   3.2. Features Left to Implement
4. Technologies Used
   4.1. Languages
   4.2. Libraries
   4.3. Other Tools
5. Testing
   5.1. Test Process
   5.2. Tests Conducted
   5.2.1. Prototype Functionality Tests
   5.2.2. Prototype Design Tests
   5.2.3. Finish Project Tests
   5.3. Test Insights
   5.3.1. Prototype Functionality Insights
   5.3.2. Prototype Design Insights
6. Deployment
7. Credits
   7.1. Content
   7.2. Media
   7.3. Acknowledgements

---

## 1. Project Background

This project is being completed as part of a Full Stack Developer Diploma award. This forms the basis for the developer's first milestone project. As such it will be completed within a set of guidelines as to which technologies to use.

While the core focus of the project is to be submitted as summative assessment for the student developers course, it is also hoped that the resource itself, and the brand created for it can be of value to the wider community.

---

## 2. UX

### 2.1. Design

Design phase goals:

- Identify user profile
- Generate user stories
- Create wireframe
- Develop brand identity
- Create high fidelity prototype
- Test high fidelity prototype

The website is conceived as a resource for hobbyist musicians who want an easy to use, aesthetically pleasing resource for Irish music. The design process is to first create a user profile which is representative of the [target user](./pre-production/fidil_user_profile.pdf).

With the target user in mind, the following user stories are generated.

- As a music enthusiast, I want to know what different instruments are used in Irish music so that I can be more aware of what I am listening to.
- As a hobbyist musician, I want to learn detailed information about individual instruments so that I can understand their various quirks and idiosyncrasies.
- As a music enthusiast, I want to know about the different dance forms in Irish music so that I can understand why the musical forms are structured the way they are.
- As a hobbyist musician, I want to learn detailed information about each individual dance style so that I understand how to better accompany each one.
- As a music enthusiast, I want to read about Irish Music so that I can develop my own sense of Irish culture.
- As a content creator, I want to be able to contact online Irish Music platforms so that I might have my writing on the topic published.

Once the user stories are completed, [wireframes](https://xd.adobe.com/view/ddf5e229-2703-4fcc-4d65-98d347cce994-abc4/?fullscreen) are generated to form the layout of the website which allow the target user to achieve their goals. The wireframes are generated to accomodate three different screen sizes in a responsive layout:

- Macbook Pro (2019)
- iPad Pro (12.9")
- iPhone X

Next the brand is designed. This involves the creation of a [logo](#), compiling of a [color palette](#), and selection of appropriate [font choices](#).

- Creation of index.html document
- Styling of index.html using style.css and Bootstrap 4 library
- Creation of additional html pages using common elements from index.html (header, footer etc)
- Styling of additional pages
- Initial deployment on Github Pages
- Testing of deployed website
- Final adjustments
- Submission

The development phase will use only the technologies covered in the course up until the point of Milestone Project One. These include HTML and CSS only, extended by the Bootstrap 4 library. There will be no custom Javascript or other technologies included for this release. The only exception is the use of elements within Bootstrap 4 which have pre programmed javascript/jquery behaviour, which may be utilised.

Once these design choices are made, a working high fidelity [prototype](#) is constructed complete with all copy, imagery, fonts, colors, and interactions included, which is subsequently tested to verify effectiveness before development commences.

### 2.2. Development

Development phase goals

- Creation of index.html document
- Styling of index.html using style.css and Bootstrap 4 library
- Creation of additional html pages using common elements from index.html (header, footer etc)
- Styling of additional pages
- Initial deployment on Github Pages
- Testing of deployed website
- Final adjustments
- Submission

The development phase uses only the technologies covered in the course up until the point of Milestone Project One. These consist of HTML and CSS, extended by the Bootstrap 4 library. There will be no custom Javascript or other technologies included for this release. The only exception is the use of elements within Bootstrap 4 which have pre programmed javascript/jquery behaviour, which may be utilised.

The completed prototype is then annotated to show where containers, rows, columns, and other structural coding components will be. This is visible in the [annotated spec file](pre-production/spec/fidil_annotated_spec.pdf).

Once completed the [index.html](#) file is created taking care to copy & paste all available copy so as not to risk typographical erros, and thereafter the [style.css](#) file is created to style the page to match the specification, using Bootstrap where appropriate.

Additional html files are created as necessary copying common elements from the index.html file such as headers and footers. Once created, the style.css file is amended to include styling for the additional pages.

Once completed the initial deployment takes place on Github Pages, at which point it is tested.

Once final adjustments are made the project is committed to and submitted.

---

## 3. Features

### 3.1. Existing Features

- Home page - allows all users to access the top level navigation of the website, by interacting with the navigation bar, or the individual content cards.
- Instruments page - allows music enthusiasts to learn basic information about different instruments, by reading each individual instrument card.
- Instrument modal - allows hobbyist musicians to learn mroe in-depth information about each instrument by activating the individual instrument modal.
- Dances page - allows music enthusiasts to learn basic information about different dances, by reading each individual dance card.
- Dance modal - allows hobbyist musicians to learn mroe in-depth information about each dance type by activating the individual dance modal.
- History page - allows music enthusiasts to read articles about Irish Music by selecting an article using the 'Read More' feature.
- Contact modal - allows content creators to get in contact with the developer by selecting one of the contact options available in the contact modal.

### 3.2. Features Left to Implement

- MIDI playback tool
  - Develop a MIDI player which can organise tunes into sets and play them back at desired tempo to practice to.
  - Develop a sheet music visualiser for MIDI player which can highlight individual notes as they are played, and render the full set as notation.
  - Develop a instrument visualiser which can show on any traditional instrument where to place fingers to play along with MIDI player
- History database - develop a dynamic webpage which automatically organises content in the History page into searchable categories based on topic, date, and popularity.
- Tune database - develop a system for users to submit their own tunes in a way which will be compatible with the MIDI playback tool, and which will group different settings of the same tune in a simple, elegant fashion.

---

## 4. Technologies Used

In this section, I will mention all of the languages, frameworks, libraries, and any other tools that I have used to construct this project.

### 4.1. Languages

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) was used to render the content of the website.
- [CSS3](https://www.w3.org/Style/CSS/#specs) was used to style the content of the website.

### 4.2. Libraries

- [Bootstrap 4.4](https://getbootstrap.com/) was used to aid with the layout and styling of the website.
- [JQuery](https://jquery.com) was used to allow Bootstrap to function.

### 4.3. Other Tools

- [Adobe XD](#) was used to construct both wireframes and prototypes.
- [Adobe Photoshop](#) and [Adobe Illustrator](#) were used to create design assets.
- [Visual Studio Code](#) was the main IDE for this project.

---

## 5. Testing

### 5.1. Test Process

Testing is carried out at three phases to evaluate the prototypes functionality, the intuitiveness of the design, and finally verify the functionality of the final product.

Further to this, all HTML and CSS in this project is validated by using the [W3C Markup Validation Service](https://validator.w3.org/) and the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).

> Validation was completed on {**Insert date of validation here**}

### 5.2. Tests Conducted

#### 5.2.1. Prototype Functionality Tests

The function of these tests is to verify all links in the prototype lead to the expected locations, so that it is possible to proceed with testing the layout with a new user.

[Prototype functionality tests](https://we.tl/t-lNyKGpBiHT)

####5.2.2. Prototype Design Tests

The function of these tests is to ensure the design choices have resulted in an intuitive layout that facilitates first time learning and ease of locating the desired information.

The following tasks were set to the user to ensure intuitive layout:

- Find the name of a common dance style listed on the page.
- Locate information about the Bodhran on the site.
- Find the name of one important collector in irish music history.
- From the same section as the previous task, find where it states what genres irish music has had and influence on in music history.
- Find the link to get in touch with the developer through linkedin (the link will not currently click through).
- Return to the home page from any other page.

[Prototype design tests](https://we.tl/t-akHu55OIfG)

#### 5.2.3. Finish Project Tests

[Finished Project Tests](#)

### 5.3. Test Insights

The following insights were gained from the testing process.

#### 5.3.1. Prototype Functionality Insights

- Fidil Logo will lead to home page on all pages, not possible in prototype.
- Hover and click states of all links to be consistent - light color for hover, dark color for click.
- "Read More" button should have micro interaction for hover and click states.
- Modal can be closed in multiple ways, this will be retained.
- External LinkedIn & Github links will be functioning in final developed website.
- Images require standardisation across all layouts at respective resolutions and sizes.
- Bodhran photo to be corrected on phone layout.
- Font size on modals to be reduced on phone layout.

#### 5.3.2. Prototype Design Insights

- Home link not working on web history page, this will be fixed on developed website.
- Bodhran image has once again reverted to incorrect image on phone layout. Flagged to be fixed.
- Tendancy for people to go first to header for contact link, then footer. This will be accepted to separate primary navigation from secondary.
- One user reported scrolling to be arduous in their browser, will consider adding a "back to top" button in development.

---

## 6. Deployment

This project is deployed on Github Pages, which can be accessed at [Fidil Github Repo](#) or [Fidil Deployed Version](#).

> This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

> In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

> - Different values for environment variables (Heroku Config Vars)?
> - Different configuration files?
> - Separate git branch?

> In addition, if it is not obvious, you should also describe how to run your code locally.

---

## 7. Credits

### 7.1. Content

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

The svg pattern was based on a tutorial from [webdesign.tutsplus.com](https://webdesign.tutsplus.com/tutorials/how-to-use-svg-patterns-as-backgrounds--cms-31507) and updated with a customised path.

### 7.2. Media

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

### 7.3. Acknowledgements

I received inspiration for this project from:

- [Irish Traditional Music Archive](https://www.itma.ie/)
- [The Session](https://thesession.org/tunes)
- [Online Academy of Irish Music](https://www.oaim.ie/)

Thanks to David, Gillian, and Patricio for help in the testing stages.
