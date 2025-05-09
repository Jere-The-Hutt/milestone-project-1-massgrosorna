# MassGrosorna

![Responsive screen preview](assets/images/massgrosorna-responsive-preview.jpg)

## PROJECT GOALS

The goal of the project is to create a website for **MassGrosorna** publishing company so they can reach people who would be interested in buying their books. The website will feature their publications and give users a good impression of what they are selling. The site consists of four pages:
- **Home**
- **Bibliotek (Library)**
- **About**
- **Success**

The site must be clear and easy to navigate and should also provide the possibility for the user to place an order.

## TARGET AUDIENCE

- People who are interested in buying books or selling MassGrosorna's books.
- People interested in publishing their book with MassGrosorna.

## GOALS

### Buyers:
- About section describing what kind of books MassGrosorna is selling.
- Library page with all published books.
- Preview carousel of each book.
- Option to place an order.

### Retailers:
- About section describing what kind of books MassGrosorna is selling.
- Contact section with a possibility to send a message to the company.

### Collaborators:
- Contact section with a possibility to send a message to the company.

### Company:
- Sell books.
- Give a good impression of their brand.
- Gain visibility.

### Developer:
- To create a visually appealing website that complements the company's themes with family-friendly content.

## USER STORIES

| User Type        | Story                                                                 |
|------------------|------------------------------------------------------------------------|
| Book Buyer       | I'd like to preview the books before making my decision.              |
|                  | I'd like to order books from the website.                             |
|                  | I'd like to know a little about the company and the creative team.    |
| Aspiring Author  | I'd like to reach out to the company in case they are interested in publishing my story. |
|                  | I'd like to know a little about the company and the creative team.    |
| Book Retailer    | I'd like to preview the books before making my decision.              |

## DESIGN CHOICES

The company's name **MassGrosorna** is a play on the Swedish word "maskrosorna" (which translates to "The Dandelions") and also incorporates the team's family name **'Gros'**. Therefore, a logo featuring a dandelion has been created, and its color theme (yellow and green) will be used throughout the website.

### Wireframes

**Index:**

![Index](assets/images/massgrosorna-wireframe-index.png)

**Library:** 

![Library](assets/images/massgrosorna-wireframe-library.png)

**About:** 

![About](assets/images/massgrosorna-wireframe-about.png)

**Success:** 

![Success](assets/images/massgrosorna-wireframe-success.png)

### Color Palette

![Color palette](assets/images/massgrosorna-coolor-palette.jpg)

### Fonts

- **Roca** and **Jimbo-condensed-std** (Adobe Fonts)
- Fallback: **Sans-Serif**

### Imagery

- Logo / homepage hero image made with Adobe Illustrator.
- Homepage navigation card images: sourced from **Unsplash**.
- Success page: illustration from company books by **Ellinor Gros**.

## FEATURES

### Navbar

![Navbar](assets/images/massgrosorna-navbar.jpg)
- Responsive and sticky.
- Collapsible on mobile.

### Hero Image

![Hero](assets/images/massgrosorna-hero.jpg)
- Logo with site description.

### Home Page

![Home](assets/images/massgrosorna-home-page.jpg)
- Navigation cards to other pages.

### About Page

![About](assets/images/massgrosorna-about-page.jpg)
- Team member bios with profile images.

### Library Page

![Library](assets/images/massgrosorna-library-page.jpg)  
![Order modal](assets/images/massgrosorna-library-order-modal.jpg)
- Book previews and ordering.

### Success Page

![Success](assets/images/massgrosorna-success-page.jpg)
- Confirmation message after form submission.

### Footer

![Footer](assets/images/massgrosorna-footer.jpg)
- Contact form and social links.

## TECHNOLOGIES USED

- **HTML5**
- **CSS3**

### Development Tools

- **VS Code** for building the code.
- **GitHub** for storage and deployment.
- **Bootstrap** for responsive grids.
- **Coolors** for the color palette.
- **Balsamiq** for the wireframe.
- **Favicon.io** for the favicon.
- **Adobe Fonts** for the font kit.
- **Adobe Illustrator** for logo & hero design.
- **Adobe Photoshop** for image editing and optimization.

## TESTING

### Manual Testing of User Stories

| User Story                                | Page Tested        | How It's Satisfied                                                              |
|-------------------------------------------|--------------------|----------------------------------------------------------------------------------|
| Preview books before purchase             | Library            | Book cards include image carousels and descriptions.                            |
| Order books from the website              | Library            | Modal order form accessible via "Order" button.                                 |
| Learn about the company and team          | About              | "About Us" page features profile cards with team descriptions.                  |
| Contact the company to publish a story    | Footer (all pages) | Contact form in the footer lets users reach out with their story.               |
| Retailer preview of books                 | Library            | Same as for buyers – preview carousel and descriptions available.               |

### Functional Testing

- Confirm all navigation links work correctly across pages.
- Ensure modal forms open and submit correctly.
- Confirm contact form fields (Name, Email, Message) are required.
- Check if "Success" page is displayed after a successful form submission.
- Check if forms submit correctly and trigger confirmation messages or redirection.

### Responsiveness Testing

- Manually test on different devices (mobile, tablet, desktop).
- Confirm navigation bar collapses properly on smaller screens.
- Ensure carousel images resize and remain viewable.

### Validation

#### HTML

HTML code was tested using the [W3C Markup Validation Service](https://validator.w3.org/).

**Bad value error in the footer that affected all the pages.**

![Bad value error](assets/images/massgrosorna-html-validation-error.jpg)

**Fix:** Removed the space from the value.

**Warnings:**

This is most likely a language related issue and so far I have no solution for it.

![Warnings](assets/images/massgrosorna-html-validation-warnings.jpg)

If we ignore the warnings, the site passes the validation.

![HTML validation pass](assets/images/massgrosorna-html-validation-pass.jpg)

#### CSS

Passed W3C CSS Validation with no critical errors.

![CSS validation](assets/images/massgrosorna-css-validation-pass.jpg)

### Lighthouse Testing

Performance, Accessibility, Best Practices, and SEO were tested using Chrome Lighthouse:

![Lighthouse index.html](assets/images/massgrosorna-lighthouse-index-score.jpg)  
![Lighthouse library.html](assets/images/massgrosorna-lighthouse-library-score.jpg)  
![Lighthouse about.html](assets/images/massgrosorna-lighthouse-about-score.jpg)  
![Lighthouse success.html](assets/images/massgrosorna-lighthouse-success-score.jpg)

### Accessibility

Tested using [WAVE Accessibility Tool](https://wave.webaim.org/).

**Index**

![Wave index.html](assets/images/massgrosorna-wave-index.png)

**Library**

Four unidentified contrast errors. They are not visible in the Wave validator page and do not actually affect the readability of the site, so they can be ignored.

![Wave bibliotek.html](assets/images/massgrosorna-wave-library.png)

**About**

![Wave about.html](assets/images/massgrosorna-wave-about.png)

**Success**

Four unidentified contrast errors. They are not visible in the Wave validator page and do not actually affect the readability of the site, so they can be ignored.

![Wave success.html](assets/images/massgrosorna-wave-success.png)

## BUGS / ISSUES

### 1. Success Page Image Scaling on Small Screens

**Issue:**  
The image displayed on the success.html page did not scale properly on smaller screen sizes. This caused layout issues and horizontal scrolling on mobile devices.

**Fix:**  
A media query was added to adjust the image size for smaller viewports, ensuring it scales responsively and maintains the site's mobile-friendly design.

## FUTURE FEATURES

### 1. E-Commerce Integration for Library Page

To enhance user experience and streamline the purchasing process, there are plans to integrate functional e-commerce features directly into the Library page. This would allow users to:
- Add books to a shopping cart
- View their cart summary
- Checkout securely via a payment system

This functionality will provide a smoother ordering process and better support MassGrosorna's goal of increasing book sales through the site.

## DEPLOYMENT

The site is deployed using GitHub Pages.

### Steps:
1. Go to **Settings**.
2. Under **Code and automation**, select **Pages**.
3. Set source to **Deploy from Branch**.
4. Choose **main** branch and **root** folder.
5. Click **Save**.

## ATTRIBUTIONS

- **Unsplash Images**  
  - [Shallow focus photography of books by Marzie Wafa](https://unsplash.com/photos/shallow-focus-photography-of-books-lUaaKCUANVI)  
  - [White dandelion on wood by Kimberly Farmer](https://unsplash.com/photos/white-dandelion-on-brown-wooden-surface-vP9LrR7LN1U)

- **MDBootstrap Modal Template**  
  - [Bootstrap Address Form](https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/)

- **ChatGPT (OpenAI)**  
  - Used for turning homepage service cards into navigation buttons.

- **Illustrations by Ellinor Gros**  
  - Used on the Success page, from the book series *Sagor Från Landet Vid Regnbågens Slut*.
