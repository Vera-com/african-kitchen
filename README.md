
# African Kitchen

This website is focused on sharing African recipes and cooking tips for Africans in the diaspora, students who moved away from home, professional chefs, and food lovers who are willing to learn authentic African cooking. The goal is to preserve traditional African recipes and culture, connect users to culinary roots, and provide easy access to ingredients and instructional videos.

Live Site: [African Kitchen](https://vera-com.github.io/african-kitchen/)
![Mockup Preview](assets/images/techsini-mockup.png)
---

## Table of Contents

- [User Experience Section](#user-experience-section)
- [User Stories](#user-stories)
- [Design Section](#design-section)
- [Wireframes](#wireframes)
- [Mockup Preview](#mockup-preview)
- [Features](#features)
- [Future Implementations](#future-implementations)
- [Technologies Used](#technologies-used)
- [Structure](#structure)
- [Challenges Faced](#challenges-i-faced--how-i-solved-them)
- [Deployment & Local Development](#deployment--local-development)
- [Testing](#testing)
- [Credits Section](#credits-section)

---

# User Experience Section

This project is designed with real-life users in mind—Africans abroad, students away from home, and food lovers wishing to reconnect with authentic homemade African meals.

### UX (The 5 Planes)

- **Strategy**: Build a simple platform to connect users to homemade African food.
- **Scope**: Homepage, food imagery, embedded recipe videos, ingredients list, contact form, footer.
- **Structure**: One-page layout with smooth scroll navigation.
- **Skeleton**: Responsive Bootstrap grid, navbar, sections, containers.
- **Surface**: Warm earthy palette, African-style fonts, inviting visuals.

---

# User Stories

### User Story 1 — MUST-HAVE  
**As a user**, I want to view beautiful African food images to feel welcomed and emotionally connected.

### User Story 2 — MUST-HAVE  
**As a user**, I want to watch recipe videos so I can follow along while cooking.

### User Story 3 — MUST-HAVE  
**As a user**, I want to see a list of ingredients for each dish.

### User Story 4 — MUST-HAVE  
**As a user**, I would like to know if there's a way to contact or follow this site on social media.

### User Story 5 — SHOULD-HAVE  
**As a user**, I want to download recipe files for offline use.

### User Story 6 — SHOULD-HAVE  
**As a user**, I want a form to request information, send feedback, or get private training.

### User Story 7 — SHOULD-HAVE  
**As a user**, I want to share or submit my own recipes.

### User Story 8 — COULD-HAVE  
**As a user**, I’d like a cultural backstory of dishes and testimonials from others.

### User Story 9 — COULD-HAVE  
**As a user**, I want to share a favorite recipe with friends.

---

# Design Section

## Colour Scheme

| Color Name          | HEX Code  |
|---------------------|-----------|
| Rich Brown          | `#3a2620` |
| Warm Beige          | `#E8caa4` |
| Highlight Red-Orange| `#b33c12` |
| Light Peach         | `#F3a67f` |
| Deep Blue Accent    | `#416a8e` |
| Light Blue Accent   | `#7a9fc2` |

## Typography

- **Headings**: [Macondo](https://fonts.google.com/specimen/Macondo) (cursive, cultural)
- **Body Text**: [Inter](https://fonts.google.com/specimen/Inter) (clean and modern)

## Imagery

- **Hero Section**: Slideshow featuring dishes like jollof rice, okro soup, moi moi, and more.
- **Recipes Section**: Embedded YouTube videos with guides.
- **Ingredients Section**: Ingredient list with PDF downloads.

---

# Wireframes

Created with **Balsamiq Wireframes**.

### Mobile
![Mobile Wireframe](assets/images/mobile-wireframe.png)

### Tablet
![Tablet Wireframe](assets/images/tablet-wireframe.png)

### Desktop
![Desktop Wireframe](assets/images/destop-wireframe.png)

---

# Mockup Preview

Generated with [Techsini Multi-Mockup](https://techsini.com/multi-mockup/index.php) and [Am I Responsive](https://ui.dev/amiresponsive).
![Mockup Preview](assets/images/techsini-mockup.png)
![Mockup Preview](assets/images/amiresponsive.png)

---

# Features

- Responsive hero section with food slideshow.
- YouTube recipe cards: Egusi, Jollof, Oha, Ewedu & Amala.
- Downloadable PDF ingredient lists.
- Mobile-first responsive design.
- Google Form for contact/feedback.
- Sticky navbar and smooth scrolling.
- Footer with social icons.

---

## Future Implementations

- Add recipe search bar.
- Newsletter subscription form.
- Ratings & review section.
- Multilingual support.

---

# Technologies Used

- HTML5  
- CSS3 (with custom variables)  
- Bootstrap 5.3.7  
- Google Fonts  
- Font Awesome  
- JavaScript (navbar, scrolling)  
- Balsamiq (wireframe)  
- Lighthouse, W3C Validator

---

# Structure


├── index.html ├── thankyou.html ├── README.md ├── assets/ │ ├── css/ │ │ └── style.css │ ├── images/ │ │ └── [carousel, favicon, logo, meals, wireframes, mockups, tests] │ └── pdfs/ │ └── [Egusi, Jollof, Oha, Ewedu recipes]

---

# Challenges I Faced & How I Solved Them

| Issue                        | Solution |
|-----------------------------|----------|
| Git command & push issues   | Used `git pull`, fixed conflicts, then committed again |
| Sticky navbar + white gap   | Used `position: fixed`, tweaked `z-index`, and header padding |
| Missing logo                | Fixed favicon path in `<link>` |
| Video layout breaking grid  | Used Bootstrap `ratio-16x9` |
| Footer spacing too tight    | Added padding and margin |
| Form not redirecting        | Fixed with `action="thankyou.html"` |
| Color contrast (Lighthouse) | Updated button background/text for better readability |

---

# Deployment & Local Development

### Live Deployment

1. Go to your GitHub repo.
2. Click **Settings**.
3. Scroll to **Pages**.
4. Select `main` branch and `/ (root)`.
5. Click **Save** – live at GitHub Pages URL.

###  Local Development

#### Fork the repository
1. Click **Fork** in the upper right of the GitHub repo.
2. You now have your own copy.

#### Clone your fork
```bash
git clone https://github.com/your-username/african-kitchen.git
cd african-kitchen
code .


#Testing
 ## Lighthouse
Scores:
Performance: 90+
Accessibility: 100
Best Practices: 100
![Lighthouse Preview](assets/images/lighthouse-testing.png)
![Lighthouse Thankyou page](assets/images/lighthouse-thankyou-page.png)

 ## HTML Validation
 Validated using W3C HTML Validator
![W3C HTML](assets/images/w3c-validator-index.png)
![W3C Thankyou page](assets/images/w3c-validator-thankyou-html.png)

## CSS Validation
 Validated using W3C CSS Validator
![W3C CSS Validator](assets/images/w3c-validator-css.png)

## Manual Testing
Navbar scrolls properly
All images have alt text
Responsive across devices
Contact form submits to thankyou.html page.

# Credits Section
## Code Pattern
Inspired by Code Institute's Boardwalk Games structure and template.

## Fonts
Google Fonts – Macondo & Inter

## Icons
Font Awesome

## Recipe Videos
Sisi Jemimah – YouTube
Chef Lola’s Kitchen – YouTube
Sisi Yemmie – YouTube

## PDFs & Media
Recipe PDFs from personal documentation and public space like Unsplash /Pexels and a few others (not for commercial use)

Chatgpt assistance with troubleshooting to help improve clarity.

## Acknowledgements
Special thanks to:
Code Institute Slack community
Family and friends for their continuous love, support and motivation.
---


