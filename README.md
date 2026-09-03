Les Braid It: Portfolio & Booking Website

A 3-page front end web application built for Les Braid It, a hairstyling business specialising in braids, weaves, and natural hairstyles. The site gives potential clients a fast, visual way to see my work and get in touch to book.

Live site: https://llilzizl.github.io/les-braid-it-portfolio/

## Table of Contents
- [Purpose](#purpose)
- [Target Audience & User Stories](#target-audience--user-stories)
- [UX Design Rationale](#ux-design-rationale)
- [Technologies Used](#technologies-used)
- [File Structure](#file-structure)
- [Development Process](#development-process)
- [Testing](#testing)
- [Known Bugs](#known-bugs)
- [Deployment](#deployment)
- [Credits](#credits)
- [Future Improvements](#future-improvements)

##Purpose

Les Braid It needed a simple, professional web presence that does two things well:

Shows off real examples of finished work, organised by style, so a new visitor can judge quality and find the look they want at a glance
It is easy get in touch or book, either for a "Perfect" Sew In class or a collaboration/shoot, so interest converts into an actual enquiry

The goal was a site whose purpose is obvious within seconds of landing on it.

##Target audience & user stories

Primary audience: people looking to book a braiding/hairstyling appointment or class, or brands/creators looking to collaborate, likely browsing on their phone, comparing stylists before choosing one.

User stories used to guide the design:

As a potential client, I want to see photos of the stylist's previous work, grouped by style, so I can judge whether their work matches what I want.
<img width="1905" height="880" alt="image" src="https://github.com/user-attachments/assets/5eefc3f6-81bd-4640-a031-426970d1f055" />
<img width="1912" height="880" alt="image" src="https://github.com/user-attachments/assets/2cdb0141-298e-433a-a528-1418713a1bbf" />

As a potential client, I want to see a close-up of any style with more detail, so I can properly evaluate it before getting in touch.
<img width="1390" height="873" alt="image" src="https://github.com/user-attachments/assets/177eaea3-69e9-4300-8404-5d7cceaf56a8" />

As a potential client, I want an easy way to register interest or get in touch, so I don't have to hunt for contact details.
<img width="1387" height="502" alt="image" src="https://github.com/user-attachments/assets/d566cacc-7596-4198-b16c-f5ce27fa612a" />

As a brand or content creator, I want a separate, relevant way to enquire about collaborations, so my enquiry isn't mixed in with class sign-ups.
<img width="1682" height="777" alt="image" src="https://github.com/user-attachments/assets/a63cc295-fa5e-4136-97ae-3aa3f644fa53" />
<img width="1213" height="771" alt="image" src="https://github.com/user-attachments/assets/fc010aaa-f591-48dc-8e3c-54fa696bcfbe" />

As any visitor, I want to find the stylist's social profiles quickly, so I can see more of her work before committing.
<img width="1717" height="262" alt="image" src="https://github.com/user-attachments/assets/eb5e100d-c2ab-4683-aaa7-348588435d91" />

##Pages & Purpose

Home (index.html) - Introduces the brand, hero gallery of recent work, links through to the portfolio and to the two contact pathways

Portfolio (portfolio.html) - Gallery of real work across 8 styles (Perfect Sew In, Fulani, Cassie, Natural, Patewo and Base, Boho French Curl, Extra Small Layered, Pick and Drop). Tapping a photo opens a close-up view with navigation and, for the Perfect Sew In style, extra detail about the method

Contact (contact.html) - About section with photo and social links, plus two enquiry pathways: Perfect Sew In Classes and Collaborations/Shoots, each revealed only once its button is selected

Navigation is identical across all three pages so the site feels cohesive rather than three separate documents.

##UX design rationale

Information hierarchy: each page opens with the thing that matters most to a first-time visitor first (hero on the home page, gallery on the portfolio page, ways to get in touch on the contact page), so there's no scrolling to find the point of the page.
Consistency: the same nav bar, colour palette, and typography appear on every page, reinforcing a single, professional brand.

##Colour palette (matches the existing Les Braid It brand):

#0D0D0D: near-black background
#E8558F: hot pink accent, used for headings, links, buttons, and outlines
#FBE4EF: light pink, used for form labels
#B3B3B3: grey, used for supporting/body text
#FFFCF9: off-white, used for primary text on the dark background

##Colour Contrast Audit

| Foreground | Background | Used for | Ratio | AA Normal Text (4.5:1) | AA Large Text (3:1) |
|---|---|---|---|---|---|
| #FFFCF9 | #0D0D0D | Primary body text | 19.01:1 | Pass | Pass |
| #B3B3B3 | #0D0D0D | Supporting text | 9.27:1 | Pass | Pass |
| #E8558F | #0D0D0D | Headings, links, outline buttons | 5.67:1 | Pass | Pass |
| #FBE4EF | #0D0D0D | Form labels | 16.15:1 | Pass | Pass |
| #0D0D0D | #E8558F | Text on solid pink buttons | 5.67:1 | Pass | Pass |
| #FFFCF9 | #171717 | Body text inside cards | 17.54:1 | Pass | Pass |
| #B3B3B3 | #171717 | Supporting text inside cards | 8.55:1 | Pass | Pass |

<img width="926" height="842" alt="image" src="https://github.com/user-attachments/assets/cbb688f7-5974-4f1f-a484-1ac16475590c" />
<img width="927" height="842" alt="image" src="https://github.com/user-attachments/assets/cb487040-95ae-4c78-9e3f-5f65d7e1acdd" />
<img width="932" height="938" alt="image" src="https://github.com/user-attachments/assets/bc7a4ae3-a8b3-4bb6-954d-85eaac8e6240" />
<img width="937" height="837" alt="image" src="https://github.com/user-attachments/assets/52bf7fb5-e15c-444a-a656-01eee6b9124d" />
<img width="918" height="900" alt="image" src="https://github.com/user-attachments/assets/4b751142-11a7-4f1e-88d6-89b4cfd34633" />
<img width="917" height="850" alt="image" src="https://github.com/user-attachments/assets/3ef458a3-f27a-45e6-a890-c0ac4c00ea61" />
<img width="925" height="852" alt="image" src="https://github.com/user-attachments/assets/8f47bce9-412a-48c7-af90-688762e72384" />



The palette was chosen to give strong contrast between text and background for readability; a full accessibility contrast audit is still to be carried out.

I used : webaim.org/resources/contrastchecker

Progressive disclosure: the two contact forms are hidden until a visitor picks the one relevant to them, so nobody has to scroll past a form they don't need. A small "i" icon next to each option explains what it's for before committing to it.

User control: no autoplay media or pop-ups; clicking a portfolio photo, switching contact tabs, and opening an info panel all give immediate visual feedback.

Accessibility: all meaningful images include descriptive alt text; ; the gallery lightbox supports keyboard (Esc, arrow keys) and touch-swipe navigation, not just mouse clicks.

##Technologies used

HTML5 (semantic markup: `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
CSS3 (external stylesheet, custom properties for the colour palette, Flexbox and Grid layout, scroll-snap for the swipeable gallery, media queries for responsive layout)
Vanilla JavaScript (no frameworks) for the portfolio lightbox, contact tab/form switching, and info popovers
Google Fonts: Playfair Display (headings) and Montserrat (body text)
Git & GitHub for version control
GitHub Pages for deployment

## File structure

les-braid-it-portfolio/
├── index.html
├── portfolio.html
├── contact.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── main.js
    └── images/
        ├── logo.png
        ├── hero-1.jpg, hero-2.jpg, hero-3.jpg
        ├── about-photo.jpg
        ├── icons/
        │   ├── nav-home.png, nav-portfolio.png, nav-contact.png
        │   └── social-instagram.png, social-pinterest.png, social-tiktok.png, social-email.png
        └── portfolio/
            └── (photos grouped by style, e.g. fulani-1.jpg, cassie-1.jpg, natural-1.jpg, etc.)

Files and folders use lowercase names with no spaces, for cross-platform compatibility.

##Development process

Initial development was done locally, working in stages: colour palette and layout system first, then each page (home, portfolio, contact), then interactive JavaScript features (lightbox, tab switching). The working site was checked in-browser after each stage before moving on to the next.

This early local development was not committed incrementally, which is reflected in the earlier part of the commit history. From that point onward, work has been committed in smaller, more frequent stages — restructuring files into the `assets/` directory, fixing bugs found through testing (see Testing section), and documentation updates are each committed separately with descriptive messages (see commit history for details).
##Testing

Manual testing carried out so far:

Functionality: nav links, the portfolio lightbox (open/close, next/prev, swipe, info popover), and the contact page's tab switching all checked in-browser
Responsiveness: layout checked at mobile and desktop widths


 Full HTML validation against the W3C validator :
 <img width="905" height="875" alt="image" src="https://github.com/user-attachments/assets/f21c1ca4-1f41-47ba-aa8a-315947d3e0dc" />

 Before 
 <img width="1627" height="881" alt="image" src="https://github.com/user-attachments/assets/3b29ed53-6013-4e3b-822d-5b1e89a06912" />

After 
<img width="1822" height="820" alt="image" src="https://github.com/user-attachments/assets/95908f20-aaf9-439e-a920-b1bac93f1e44" />

Before 
<img width="1865" height="777" alt="image" src="https://github.com/user-attachments/assets/6d992fd2-2913-4265-977f-aa216fbc6a4c" />

After
<img width="1886" height="530" alt="image" src="https://github.com/user-attachments/assets/d19a7527-040e-43e4-8778-03d13f88073b" />

 Full CSS validation against the Jigsaw validator
 <img width="1808" height="821" alt="image" src="https://github.com/user-attachments/assets/59bf4fae-0182-4eb7-a8ad-3554e7ab7913" />

 Cross-browser check (Chrome, Firefox, Safari, Edge)
 
 Works with all browsers
 
 Tablet-width check

 Works with tablet width : 
 <img width="932" height="773" alt="image" src="https://github.com/user-attachments/assets/db9b4dc8-8151-4c3d-be92-46f860b23ae3" />

Testing Log :

| # | Bug | Where | Fix |
|---|---|---|---|
| 1 | Logo had large transparent padding baked into the PNG, so no CSS height increase made it look bigger | `images/logo.png` | Cropped the file to the actual artwork bounds |
| 2 | Header spacing pushed logo far from the border line / then too close after first fix | `style.css` `.site-header` | Iterated `padding` and `align-items` until spacing looked right |
| 3 | Hero gallery images broken (referenced `.png`, actual files were `.jpg`) | `index.html` | Removed the hero-gallery section entirely (your choice) |
| 4 | Lightbox info panel content got cut off with no way to scroll to see the rest | `style.css` `.lightbox` | Added `overflow-y: auto` and switched `align-items` to `flex-start` |
| 5 | Both "more info" popovers on the contact page could be open at the same time | `main.js` | Rewrote toggle logic to close all panels before opening the clicked one |
| 6 | 39 HTML validation errors: `<figure>` not allowed inside `<button>` | `portfolio.html` | Removed the unnecessary `<figure>` wrapper around each thumbnail image |
| 7 | HTML validation error: `<img src="">` is invalid (empty but present) | `portfolio.html` lightbox | Replaced with a tiny valid placeholder image |
| 8 | HTML validation errors: mismatched `<section>`/`<div>` opening and closing tags | `portfolio.html` | Made opening and closing tags match |
| 9 | HTML validation warning: `.about-strip` section had no heading | `contact.html` | Added a visually-hidden `<h2>About</h2>` |
| 10 | Decorative background images (`bg-decor-*.png`) rendered too small/faint | `index.html`, `contact.html`, `style.css` | Removed entirely (your choice) |


##Known bugs

None    

##Deployment

The site is deployed via GitHub Pages:

Push the final code to the main branch on GitHub
In the repository, go to Settings → Pages
Select the main branch as the source
GitHub Pages generates a live URL, which is tested to confirm it matches the local development version

##Credits

Design and development by Lilian, for Les Braid It
- Claude Code (AI assistance used for debugging and documentation support)

Photography of finished styles by Lilian / Les Braid It

Fonts: Google Fonts, Playfair Display, Montserrat

##Future improvements

- Services and pricing page/table
- Client testimonials
- Opening hours and location details
- Online booking calendar integration, rather than static contact forms
- Actual form submission handling (currently front-end only)
- Client login/portal for repeat bookings
- Filtering the portfolio gallery by hairstyle type
