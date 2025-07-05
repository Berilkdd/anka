
# Anka – Artisans of Rebirth

A static, user-centric front-end website connecting artisan producers from Türkiye and Syria with supportive communities in the UK. Visitors can browse handmade products, learn about the makers' stories, and offer shelf space to support recovery through tradition.

---

## Table of Contents

- [User Experience (UX)](#user-experience-ux)
- [Features](#features)
- [User Stories](#user-stories)
- [Design](#design)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

---

## User Experience (UX)

### Strategy
- **Project goal:** Connect artisan earthquake/war survivors with UK-based small businesses to promote recovery through craft.
- **Target audience:** UK shop owners, ethical consumers, and supporters interested in global solidarity.

### Scope
- Allow users to browse products by category (Pantry / Atelier).
- Provide background stories of artisans.
- Enable easy offer of shelf space via a form.

### Structure
- Homepage > Section Page > Product Grids > Form Page > Success Page
- Navigation links: Home, Products, Offer a Shelf

### Skeleton
- Mobile-first responsive layout using Bootstrap Grid.
- Carousel for stories, simple CTAs, and form validation.

### Surface
- Color palette with earth tones and natural beige backgrounds.
- Serif and sans-serif font combination via Google Fonts.
- Consistent image ratios and content spacing.

---

## Features

- **Fully responsive design** across all screen sizes
- **Carousel of real artisan stories** on the homepage
- **Clear CTA buttons** for product exploration and shelf offering
- **Dedicated Pantry and Atelier sections**
- **Accessible, validated shelf form** with success message

---

## User Stories

<details>
<summary>Click to expand all user stories</summary>

### Must-Have

#### **User Story 1: Mobile-friendly navigation and responsive design**
_As a First-Time Visitor, I need intuitive navigation and a responsive design so I can access Anka’s content easily on my phone or desktop._

**Acceptance Criteria:**
- Works across devices
- Simple navbar: Home, Products, Offer a Shelf
- Sticky or hamburger nav

**Tasks:**
- Responsive Bootstrap layout
- Simplified navbar structure

---

#### **User Story 2: Impactful homepage with mission and stories**
_As a Curious Visitor, I want to immediately understand what Anka does and feel inspired by its impact._

**Acceptance Criteria:**
- Clear headline, short mission
- Carousel with portraits/quotes
- Main CTA + subtle shelf link

**Tasks:**
- Build structured homepage
- Connect carousel to story grid

---

#### **User Story 3: View artisan product categories and items**
_As a Shop Owner, I want to browse Pantry and Atelier separately so I can decide what fits my store._

**Acceptance Criteria:**
- Section intro with two blocks
- Separate product grids
- Labels with region/producer

**Tasks:**
- Grid-based layout for products
- Reusable label design system

---

#### **User Story 4: Simple form to offer shelf space**
_As a Supporter, I want to fill in a form to offer shelf space so I can be contacted by Anka._

**Acceptance Criteria:**
- Fields: Name, Shop, Email, Address, Phone
- Redirect to poetic success message

**Tasks:**
- Form with validation
- Success page confirmation

---

### Should-Have

#### **User Story 5: Access shelf form directly from homepage**
_As a Returning Visitor, I want to go straight to the form so I don’t need to browse again._

**Acceptance Criteria:**
- Link below homepage CTA
- Persistent navbar link

**Tasks:**
- Low-weight shelf CTA styling

---

#### **User Story 6: Understand producers behind each product**
_As a Shop Owner, I want to see who made each item so I can share their story with my customers._

**Acceptance Criteria:**
- Structured label text
- Uniform product tile style

**Tasks:**
- Design and add short labels

---

### Could-Have

#### **User Story 7: Add a personal story carousel or testimonial section**
_As a Visitor, I want to hear from real people so I feel more confident in Anka’s mission._

**Acceptance Criteria:**
- Story cards with names/faces
- Mobile-friendly carousel

**Tasks:**
- Add carousel to homepage
- Populate with authentic story visuals

</details>

---

## Design

- **Fonts:** Crimson Text (headings), Inter (body), Quicksand (logo)
- **Colors:**  
  - Warm Beige `#f4efe7`  
  - Dark Green `#2b674b`  
  - Soft Terracotta `#b8583c`  
  - Midnight Gray `#4a4a4a`
- **Wireframes:** Created in Figma ([view here](https://www.figma.com/design/dz9qBsNOYxKX5iWGIIndAN))
- Design evolved from initial mockups based on content flow.

---

## Technologies Used

- HTML5
- CSS3
- Bootstrap 5
- Font Awesome
- Google Fonts

---

## Testing

### HTML Validation  
All HTML files were tested using the official [W3C HTML Validator](https://validator.w3.org/).  
All pages passed with **no errors**.

#### HTML Validation Screenshots  
Screenshots of each HTML page’s validation result are included below as evidence of successful validation:

##### Homepage
![Homepage HTML Validation](assets/images/test-screenshots/index-html-test.png)

##### Pantry Page
![Pantry HTML Validation](assets/images/test-screenshots/anka-pantry-html-test.png)

##### Atelier Page
![Atelier HTML Validation](assets/images/test-screenshots/anka-atelier-html-test.png)

##### Products Page
![Products HTML Validation](assets/images/test-screenshots/products-html-test.png)

##### Success Page
![Success HTML Validation](assets/images/test-screenshots/success-html-test.png)

### CSS Validation  
Custom CSS was tested using the official [Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input).  
No errors were detected.

### Lighthouse Audit  
Lighthouse tests were conducted using Chrome DevTools for both **mobile** and **desktop** views.

**Mobile:**
- **Performance**: 70  
- **Accessibility**: 95  
- **Best Practices**: 96  

**Desktop:**
- **Performance**: 97  
- **Accessibility**: 96  
- **Best Practices**: 96  

While the mobile performance score is lower, key areas like accessibility and best practices remain strong. Improvements were identified but deprioritized due to time constraints.

### Manual Testing  
- Navigation and layout tested on desktop, tablet, and mobile devices  
- All links and buttons route correctly  
- Form validates required fields before submission  
- Success page displays after form submission  
- Images load properly with alt text for accessibility  
- External links open in new tabs (`target="_blank"` and `rel="noopener"` applied)

## Deployment

- Project was developed in VS Code and version-controlled with Git
- Hosted via GitHub Pages: [Live Site Link](https://berilkdd.github.io/anka/)
- Repository: [GitHub Repository](https://github.com/Berilkdd/anka)

To run locally:
```bash
git clone https://github.com/Berilkdd/anka.git
```

---

## 🧾 Credits

### Content & Design:
- All product data, user stories, and design provided by project creator
- Logo adapted from **Adobe Stock**, credited to **TAOFIK**

### Images:
- All story images and artisan portraits generated with assistance from ChatGPT (DALL·E) and modified/customized for the project

### Resources:
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


