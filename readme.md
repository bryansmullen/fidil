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
   5.2. Test Insights
6. Deployment
7. Credits
   7.1. Content
   7.2. Media
   7.2.1. Pre-production User Profile
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

The completed prototype is then annotated to show where containers, rows, columns, and other structural coding components will be. This is visible in the [red-line drawing](#).

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

All HTML and CSS in this project is validated by using the [W3C Markup Validation Service](https://validator.w3.org/) and the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).

> Validation was completed on {**Insert date of validation here**}

User testing took place at two specific points during the production. First, at the design stage, the prototype was tested using unmoderated testing to verify that all user goals could be achieved. Second, the finished website was tested using unmoderated testing to verify that the final product behaved as expected.

### 5.2. Test Insights

The following was observed from the testing.

> **FILL THIS IN WITH DATA LATER**

Results of the user testing are available here:
[Prototype Test 1](#)
[Prototype Test 2](#)
[Prototype Test 3](#)
[Finished Project Test 1](#)
[Finished Project Test 2](#)
[Finished Project Test 3](#)

> In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

> Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

> For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

> 1. Contact form:
> 1. Go to the "Contact Us" page
> 1. Try to submit the empty form and verify that an error message about the required fields appears
> 1. Try to submit the form with an invalid email address and verify that a relevant error message appears
> 1. Try to submit the form with all inputs valid and verify that a success message appears.

> In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

> You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

> If this section grows too long, you may want to split it off into a separate file and link to it from here.

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

This readme file was based on content provided by [Code Institute](https://codeinstitute.net/)

> - The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### 7.2. Media

The photos used in this site were obtained from:

- Pre-production User Profile
  - Fence Photo by Ana Cruz on Unsplash
  - Mark Photo by ThisisEngineering RAEng on Unsplash
  - Sarah Photo by Annie Spratt on Unsplash
  - James Photo by Andrea Piacquadio from Pexels
  - User Profile Template from Bring Your Own Laptop UX/UI Design Course Files

### 7.3. Acknowledgements

I received inspiration for this project from:

- [Irish Traditional Music Archive](https://www.itma.ie/)
- [The Session](https://thesession.org/tunes)
- [Online Academy of Irish Music](https://www.oaim.ie/)
