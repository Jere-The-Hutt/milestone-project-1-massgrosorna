# MassGrosorna

![Responsive screen preview](assets/images/massgrosorna-responsive-preview.jpg)

## PROJECT GOALS
The goal of the project is to create a website for **MassGrosorna** publishing company so they can reach people who would be interested in buying their books. The website will feature their publications and give users a good impression of what they are selling. The site will consist of four pages:
- **Home**
- **Bibliotek (Library)**
- **About**
- **Success**

The site must be clear and easy to navigate and should also provide the possibility for the user to place an order.

## TARGET AUDIENCE
- People who are interested in buying books or selling MassGrosorna's books.
- People interested in publishing their book with MassGrosorna.

## USER STORIES
### 1. As someone who is interested in buying children's books:
- I'd like to preview the books before making my decision.
- I'd like to order books from the website.
- I'd like to know a little about the company and the creative team.

### 2. As someone who is interested in publishing a book:
- I'd like to reach out to the company in case they are interested in publishing my story.
- I'd like to know a little about the company and the creative team.

### 3. As someone who is interested in selling children's books in my shop:
- I'd like to preview the books before making my decision.

## TESTING USER STORIES
**1. I'd like to preview the books before making my decision.**
- The library page features cards for each book, including a carousel for three preview pages and a description of the contents.

**2. I'd like to order books from the website.**
- The library page features a modal with a form that the user can use to leave their order request. It can be opened with a button beneath the library cards.

**2. I'd like to know a little about the company and the creative team.**
- The about us page features cards for each team member with a profile picture, name and a job description.

## GOALS
### Buyers:
- About section describing what kind of books MassGrosorna is selling.
- Library page with all published books.
- Preview carousel of each book.
- Option to place an order.

### Retailers:
- About section describing what kind of books MassGrosorna is selling.
- Contact section with a possibility to send a message to the company.

### For collaborators:
- Contact section with a possibility to send a message to the company.

### Company goals:
- Sell books.
- Give a good impression of their brand.
- Gain visibility.

### Dev goals:
- To create a visually appealing website that complements the company's themes with family-friendly content.

## DESIGN CHOICES
The company's name **MassGrosorna** is a play on the Swedish word "maskrosorna" (which translates to "The Dandelions") and also incorporates the team's family name **'Gros'**. Therefore, a logo featuring a dandelion has been created, and its color theme (yellow and green) will be used throughout the website.

### Colors:
![Color palette from Coolor](assets/images/massgrosorna-coolor-palette.jpg)

### Fonts:
**Roca** and **Jimbo-condensed-std** from **Adobe Fonts**. I chose these as they went nicely with the friendly feeling of the website. They are also easy to read and not too childish, as the main user of the website is more likely the parent.

**Sans-Serif** as the fallback font to make sure that, if the chosen fonts aren't available, a clean, modern, and easily readable font is used.

### Imagery:
Imagery for the homepage was found from **https://www.unsplash.com**. 

Link for the *Hem* (Library) page by **Marzie Wafa**.
[Shallow focus photography of books](https://unsplash.com/photos/shallow-focus-photography-of-books-lUaaKCUANVI)

Link image for the *Om Oss* (About us) page by **Kimberly Farmer**.
[White dandelion on brown wooden surface](https://unsplash.com/photos/white-dandelion-on-brown-wooden-surface-vP9LrR7LN1U)

Image for the success page is taken from the book series *"Sagor från landet vid regnbågens slut"* illustrated by **Ellinor Gros**. These images provide an immediate impression of what the company represents.

## FEATURES

### Navbar:
![Navbar](assets/images/massgrosorna-navbar.jpg)
- Company logo on the left side.
- Links: Home, Library, About us.
- Collapses on smaller devices.
- Fixed to the top.

### Hero Image:
![Hero](assets/images/massgrosorna-hero.jpg)
- The company logo featuring a dandelion with the company name **MassGrosorna** with a brief description of the company.

### Home Page:
![Home](assets/images/massgrosorna-home-page.jpg)
- The homepage also has service cards that acts as buttons so the user can easily navigate to the other pages.

### About Page:
![About us](assets/images/massgrosorna-about-page.jpg)
- Provides relevant information about the company, the creative team, and its focus.
- Features cards with pictures and descriptions of each member and their roles.
- Fully responsive.

### Library Page:
![Library](assets/images/massgrosorna-library-page.jpg)
![Order modal](assets/images/massgrosorna-library-order-modal.jpg)
- Displays cards for all releases, each with a description and a three-image carousel for previews.
- Includes a button that opens a modal form for placing an order. I used the address form example from **[MDBootsrap](https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/)**.
- Fully responsive.

### Success Page:
![Success](assets/images/massgrosorna-success-page.jpg)
- Displays a success message when a user submits an order or a contact request.

### Footer:
![Footer](assets/images/massgrosorna-footer.jpg)
- Contains the company's contact form.
- Includes social media links.
- **Form fields:** Name, Email, and Message.

## TECHNOLOGY USED
- **HTML5**
- **CSS3**

### Tools and Libraries:
- **VS Code** for building the code.
- **GitHub** for storage and deployment.
- **Bootstrap** for responsive grids.
- **Coolors** for the color palette.
- **Balsamiq** for the wireframe.
- **Adobe Fonts** for the font kit.
- **ChatGPT (OpenAI)** to turn the **services** cards in to navigation buttons on the homepage.
- **[MDBootsrap](https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/)** for the modal contact form example.

## VALIDATION

### HTML
**Error:**

Bad value error in the footer that affected all the pages.
![Error bad value](assets/images/massgrosorna-html-validation-error.jpg)
**Fix:** Removed the space from the value.

**Warnings:**

![Text run warning](assets/images/massgrosorna-html-validation-warnings.jpg)
**This is most likely a language related issue and so far I have no solution for it.**

### CSS
**No errors:**

![CSS validation passed](assets/images/massgrosorna-css-validation-pass.jpg)

### Lighthouse

#### index.html
![Lighthouse index.html](assets/images/massgrosorna-lighthouse-index-score.jpg)

#### bibliotek.html
![Lighthouse library.html](assets/images/massgrosorna-lighthouse-library-score.jpg)

#### index.html
![Lighthouse about.html](assets/images/massgrosorna-lighthouse-about-score.jpg)

#### index.html
![Lighthouse success.html](assets/images/massgrosorna-lighthouse-success-score.jpg)

### WAVE accessibility

## Deployment

The site was deployed by using GitHub
### Steps:
**1.** Open **settings**.

**2.** Under **Code and automation**, select **Pages**.

**3. Settings:**
- Set source to **Deploy from Branch**
- Select **Main branch**
- Set **Folder** to **/(root)**

**4.** Save.


