# Project-1: Awaiz Clothing

A multi-page front-end website for "Awaiz Clothing", a fictional clothing store.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

## Overview

I built this site to improve my web development skills, with a focus on clear section structure, spacing with padding and margins, and a responsive, easy-to-use layout. It is front-end only: there is no backend, so the forms don't send data anywhere.

## Pages

| Page | Content |
|---|---|
| `index.html` | Home page with a video hero, new arrivals filterable by Women, Accessories and Men, promotional banners, service highlights (free shipping over 100 AED, fast delivery, 45-day returns, open every day) |
| `categories.html`, `manCategories.html`, `aksCategories.html`, `newCategories.html` | Women's, men's, bags and new-arrivals listings, with sidebar filters for category, size, colour and shoe size |
| `single.html` | Product details and a review form |
| `card.html` | Shopping cart with coupon code and order summary |
| `pay.html` | Checkout with billing details and an optional separate shipping address. *Complete Payment* opens `thankyou.html` |
| `thankyou.html` | Order confirmation |
| `contact.html` | Contact details and a contact form |

Every page has a navigation bar and a newsletter subscription form in the footer.

## Tech Stack

- HTML, CSS and JavaScript (jQuery)
- Bootstrap 4.4 for the grid, plus `styles/allResponsive.css`
- Swiper sliders, Isotope product filtering, AOS scroll animations and Font Awesome icons, all loaded from CDNs

## Getting Started

There is no build step. Open `index.html` in a browser, or serve the folder locally:

```bash
git clone https://github.com/4waiz/Project-1.git
cd Project-1
python -m http.server 8000   # then open http://localhost:8000
```

You need an internet connection for the CDN-hosted libraries.

## Project Structure

```
Project-1/
├── index.html, categories.html, manCategories.html, aksCategories.html, newCategories.html
├── single.html, card.html, pay.html, thankyou.html, contact.html
├── styles/   # page stylesheets and responsive rules
├── js/       # jQuery page scripts (menu, header, filtering, sliders)
├── images/   # product, banner and slider images
└── videos/   # home page hero video
```

---

Built by [Awaiz Ahmed](https://github.com/4waiz)
