Les Braid It: Portfolio & Booking Website

A 3-page front end web application built for Les Braid It, a hairstyling business specialising in braids, weaves, and natural hairstyles. The site gives potential clients a fast, visual way to see my work and get in touch to book.

Live site:  xx

Purpose

Les Braid It needed a simple, professional web presence that does two things well:

Shows off real examples of finished work, organised by style, so a new visitor can judge quality and find the look they want at a glance
Makes it effortless to get in touch or book, either for a "Perfect" Sew In class or a collaboration/shoot, so interest converts into an actual enquiry

The goal was a site whose purpose is obvious within seconds of landing on it.

Target audience & user stories

Primary audience: people looking to book a braiding/hairstyling appointment or class, or brands/creators looking to collaborate, likely browsing on their phone, comparing stylists before choosing one.

User stories used to guide the design:

As a potential client, I want to see photos of the stylist's previous work, grouped by style, so I can judge whether their work matches what I want.
As a potential client, I want to see a close-up of any style with more detail, so I can properly evaluate it before getting in touch.
As a potential client, I want an easy way to register interest or get in touch, so I don't have to hunt for contact details.
As a brand or content creator, I want a separate, relevant way to enquire about collaborations, so my enquiry isn't mixed in with class sign-ups.
As any visitor, I want to find the stylist's social profiles quickly, so I can see more of her work before committing.

Pages	Purpose
Home (index.html)	Introduces the stylist and brand, hero gallery of recent work, links through to the portfolio and to the two contact pathways
Portfolio (portfolio.html)	Gallery of real work across 8 styles (Perfect Sew In, Fulani, Cassie, Natural, Patewo and Base, Boho French Curl, Extra Small Layered, Pick and Drop). Tapping a photo opens a close-up view with navigation and, for the Perfect Sew In style, extra detail about the method
Contact (contact.html)	About section with photo and social links, plus two enquiry pathways: Perfect Sew In Classes and Collaborations/Shoots, each revealed only once its button is selected

Navigation is identical across all three pages so the site feels cohesive rather than three separate documents.

UX design rationale
Information hierarchy: each page opens with the thing that matters most to a first-time visitor first (hero on the home page, gallery on the portfolio page, ways to get in touch on the contact page), so there's no scrolling to find the point of the page.
Consistency: the same nav bar, colour palette, and typography appear on every page, reinforcing a single, professional brand.

Colour palette (matches the existing Les Braid It brand):
#0D0D0D: near-black background
#E8558F: hot pink accent, used for headings, links, buttons, and outlines
#FBE4EF: light pink, used for form labels
#B3B3B3: grey, used for supporting/body text
#FFFCF9: off-white, used for primary text on the dark background

The palette was chosen to give strong contrast between text and background for readability; a full accessibility contrast audit is still to be carried out (see Testing).

Progressive disclosure: the two contact forms are hidden until a visitor picks the one relevant to them, so nobody has to scroll past a form they don't need. A small "i" icon next to each option explains what it's for before committing to it.
User control: no autoplay media or pop-ups; clicking a portfolio photo, switching contact tabs, and opening an info panel all give immediate visual feedback.
Accessibility: all meaningful images include descriptive alt text; purely decorative images (background flourishes) are marked with empty alt attributes so screen readers skip them; the gallery lightbox supports keyboard (Esc, arrow keys) and touch-swipe navigation, not just mouse clicks.
Technologies used
HTML5 (semantic markup: <header>, <nav>, <main>, <section>, <footer>)
CSS3 (external stylesheet, custom properties for the colour palette, Flexbox and Grid layout, scroll-snap for the swipeable gallery, media queries for responsive layout)
Vanilla JavaScript (no frameworks) for the portfolio lightbox, contact tab/form switching, and info popovers
Google Fonts: Playfair Display (headings) and Montserrat (body text)
Git & GitHub for version control
GitHub Pages for deployment

## File structure

```
les-braid-it-portfolio/
├── index.html
├── portfolio.html
├── contact.html
├── style.css
├── main.js
├── README.md
└── images/
    ├── logo.png
    ├── about-photo.jpg
    ├── hero-1.jpg, hero-2.jpg, hero-3.jpg
    ├── icons/
    │   ├── nav-home.png, nav-portfolio.png, nav-contact.png
    │   └── social-instagram.png, social-pinterest.png, social-tiktok.png, social-email.png
    └── portfolio/
        └── (photos grouped by style, e.g. fulani-1.jpg, cassie-1.jpg, natural-1.jpg, etc.)
```

Files and folders use lowercase names with no spaces, for cross-platform compatibility.

Development process

The site was built and version-controlled with Git throughout. Development happened in stages: palette and layout system first, then each page, then the interactive JavaScript (lightbox, tab switching), with the working site checked in the browser after each stage before moving on.

Testing

Manual testing carried out so far:

Functionality: nav links, the portfolio lightbox (open/close, next/prev, swipe, info popover), and the contact page's tab switching all checked in-browser
Responsiveness: layout checked at mobile and desktop widths

Still to do before this is submission-ready:

 Full HTML validation against the W3C validator
 Full CSS validation against the Jigsaw validator
 Formal colour contrast check (e.g. WebAIM contrast checker) against WCAG AA
 Cross-browser check (Chrome, Firefox, Safari, Edge)
 Tablet-width check
 Form field testing (empty submission, invalid email, etc.) once a submission backend is added

[Add a testing log here: table of what was tested, expected result, actual result, pass/fail]

Known bugs

[List anything not yet fixed, and why, e.g. "contact forms don't currently submit anywhere; no backend is connected yet, so this is expected at this stage, not a bug."]

Deployment

The site is deployed via GitHub Pages:

Push the final code to the main branch on GitHub
In the repository, go to Settings → Pages
Select the main branch as the source
GitHub Pages generates a live URL, which is tested to confirm it matches the local development version
Credits
Design and development by Lilian, for Les Braid It
Photography of finished styles by Lilian / Les Braid It
Fonts: Google Fonts, Playfair Display, Montserrat
Future improvements
Services and pricing page/table
Client testimonials
Opening hours and location details
Online booking calendar integration, rather than static contact forms
Actual form submission handling (currently front-end only)
Client login/portal for repeat bookings
Filtering the portfolio gallery by hairstyle type


