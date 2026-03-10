# 🌍 Explore the World

**A responsive front-end travel booking website showcasing beautiful destinations around the globe.**

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Course Information](#course-information)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Pages](#pages)
- [Destinations](#destinations)
- [Responsive Design](#responsive-design)
- [How to Use](#how-to-use)
- [Credits](#credits)

---

## 🎯 Project Overview

**Explore the World** is a front-end travel booking website designed for college coursework. The website showcases 10 popular travel destinations worldwide with beautiful imagery, detailed descriptions, and pricing information. Users can browse destinations, watch travel inspiration videos, and contact the travel agency through an interactive contact form.

This is a **static website** (HTML5 + CSS3 only) that demonstrates responsive design principles and modern web development practices.

---

## 🎓 Course Information

- **Course:** Web Development and Internet Applications
- **Semester:** Winter 2025
- **Institution:** Fanshawe College
- **Student:** Christiane Nogueira Mendes
- **Student ID:** 1242980
- **Project Type:** Front-End Development
- **Submission:** Front-End Project

---

## ✨ Features

- 🗺️ **10 Travel Destinations** - Beautifully showcased with high-quality images and descriptions
- 💰 **Pricing Information** - Per-person pricing in Canadian dollars for each destination
- 📱 **Fully Responsive Design** - Optimized for mobile (320px+), tablet (820px+), and desktop (1200px+)
- 📧 **Interactive Contact Form** - Easy-to-use form to inquire about bookings
- 🎨 **Modern UI/UX** - Clean, professional design with smooth animations
- 🎥 **Embedded YouTube Video** - Travel inspiration video about Canada
- 📍 **Social Media Integration** - Links to Facebook, Instagram, Pinterest, and X (Twitter)
- 🎠 **Auto-Rotating Carousel** - Image carousel with smooth animations
- ♿ **Accessibility Features** - Proper alt text, semantic HTML, and focus states
- ⚡ **Performance Optimized** - Lightweight CSS and optimized images

---

## 📁 Project Structure

```
explore-the-world/
├── index.html              # Main landing page with destination gallery
├── contact.html            # Contact form and inquiry page
├── css/
│   ├── style.css           # Main stylesheet (global styles, layouts)
│   └── queries.css         # Media queries for responsive design
├── images/                 # Destination photos and assets
│   ├── logo.png
│   ├── background.jpg
│   ├── amsterdam.jpg
│   ├── bangkok.jpg
│   ├── dubai.jpg
│   ├── london.jpg
│   ├── nyc.jpg
│   ├── paris.jpg
│   ├── rio.jpg
│   ├── rome.jpg
│   ├── sidney.jpg
│   ├── toronto.jpg
│   ├── image2.jpg          # Carousel image
│   ├── image3.jpg          # Carousel image
│   └── image4.jpg          # Carousel image
└── README.md               # This file
```

---

## 🛠️ Technologies Used

### Frontend Technologies

- **HTML5** - Semantic markup and document structure
- **CSS3** - Modern styling, animations, and layouts
  - Flexbox for responsive layouts
  - Media queries for mobile-first responsive design
  - CSS animations and transitions
  - Gradient backgrounds
  - Box-shadow effects

### External Resources

- **Google Fonts** - Dancing Script (headings) and Roboto (body text)
- **Font Awesome 6** - Social media icons
- **YouTube Embed** - Travel inspiration video

### Tools & Platforms

- **Git & GitHub** - Version control and repository management
- **Visual Studio Code** - Code editor

---

## 📄 Pages

### 1. **Home Page (index.html)**

The main landing page featuring:

#### Header

- Logo and site title
- Navigation menu (Home / Contact)

#### Hero Section

- Welcome message: "Welcome to Your Next Adventure!"
- Call-to-action message

#### Auto-Rotating Carousel

- 3 travel-themed images that automatically rotate
- Smooth transitions every 9 seconds

#### About Section

- Intro text about the travel agency
- Description of travel packages
- Company mission statement
- Embedded YouTube video about amazing places in Canada

#### Destinations Gallery

10 featured destinations:

1. **Amsterdam** - CA$950.00
2. **Bangkok** - CA$780.00
3. **London** - CA$980.00
4. **New York City** - CA$1,050.00
5. **Paris** - CA$990.00
6. **Sydney** - CA$1,150.00
7. **Rome** - CA$910.00
8. **Rio de Janeiro** - CA$850.00
9. **Dubai** - CA$1,200.00
10. **Toronto** - CA$860.00

Each destination includes:

- High-quality image
- Destination name
- Description
- Price per person
- "Book Now" button

#### Social Media Section

- Follow us message
- Links to social media platforms (Facebook, Instagram, Twitter, Pinterest)

#### Footer

- Copyright information
- Designer attribution

---

### 2. **Contact Page (contact.html)**

The contact and inquiry page featuring:

#### Contact Introduction

- Welcome message
- Phone number: 1-800-555-0199
- Email: c_nogueiramendes@fanshaweonline.ca

#### Contact Form

Interactive form with fields for:

- **Name** (required)
- **Email** (required)
- **Message** (required)
- **Phone** (optional)
- **Address** (optional)
- Submit button

#### Work With Us Section

- Collaboration and partnership information
- Partnership email: c_nogueiramendes@fanshaweonline.ca

#### Social Media Links

- Links to Facebook, Instagram, Pinterest, and X (Twitter)
- Social media icons with hover effects

#### Footer

- Same footer as home page

---

## 🌍 Destinations

| Destination       | Price    | Region        | Highlights                          |
| ----------------- | -------- | ------------- | ----------------------------------- |
| 🇳🇱 Amsterdam      | CA$950   | Europe        | Canals, Bicycles, Art               |
| 🇹🇭 Bangkok        | CA$780   | Asia          | Temples, Markets, Street Food       |
| 🇬🇧 London         | CA$980   | Europe        | Landmarks, Culture, History         |
| 🗽 New York City  | CA$1,050 | North America | Icons, Entertainment, Fast-Paced    |
| 🗼 Paris          | CA$990   | Europe        | Art, Cuisine, Romance               |
| 🇦🇺 Sydney         | CA$1,150 | Oceania       | Beaches, Landmarks, Outdoor Life    |
| 🇮🇹 Rome           | CA$910   | Europe        | Ancient Ruins, Art, Italian Cuisine |
| 🇧🇷 Rio de Janeiro | CA$850   | South America | Landscapes, Beaches, Energy         |
| 🇦🇪 Dubai          | CA$1,200 | Middle East   | Luxury, Architecture, Shopping      |
| 🇨🇦 Toronto        | CA$860   | North America | Culture, Art, Urban Charm           |

---

## 📱 Responsive Design

The website is fully responsive with three breakpoints:

### Mobile First (0px - 819px)

- Single-column layout
- Vertical navigation menu
- Full-width images
- Optimized touch targets
- Stacked form elements

### Tablet (820px - 1199px)

- 2-column layouts for gallery items
- Horizontal navigation menu
- Larger text sizes for readability
- Optimized spacing and padding

### Desktop (1200px+)

- 3-column gallery grid
- Full-width layouts
- Enhanced hover effects
- Optimized whitespace
- Professional spacing

#### Key Responsive Features:

- Flexible grid layouts using Flexbox
- Responsive images with `object-fit: cover`
- Media queries for different screen sizes
- Font scaling based on viewport
- Adaptive navigation menu
- Touch-friendly button sizes on mobile

---

## 🚀 How to Use

### Option 1: View Online

The website can be deployed to hosting services like:

- GitHub Pages
- Vercel
- Netlify
- Any web hosting provider

### Option 2: Run Locally

#### Prerequisites:

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (optional, for viewing source code)

#### Steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/christianenogm/explore-the-world.git
   cd explore-the-world
   ```

2. **Open in your browser:**
   - Double-click `index.html` to open it directly
   - OR use a local server (recommended):

     **Using Python 3:**

     ```bash
     python -m http.server 8000
     ```

     Then visit: `http://localhost:8000`

     **Using VS Code Live Server:**
     - Install Live Server extension
     - Right-click `index.html` → "Open with Live Server"

3. **Navigate the website:**
   - Browse destinations on the home page
   - Explore destination cards and descriptions
   - Watch the travel video
   - Visit the Contact page to view the contact form
   - Click social media links

---

## 🎨 Design Highlights

### Color Scheme

- **Primary Blue:** `#0077b6` - Main brand color
- **Dark Blue:** `#023e8a` - Headings and accents
- **Light Blue:** `#55bbf7d4` - Background accents
- **White:** `#ffffff` - Clean backgrounds
- **Grey:** `#d3d3d3` - Borders and dividers

### Typography

- **Headings:** Dancing Script (Google Fonts)
- **Body Text:** Roboto 400, 500, 700 weights
- **Font Sizes:** Responsive, scales with viewport

### Animations & Effects

- Fade-in animations on page load
- Auto-rotating carousel (9s duration)
- Hover effects on destination cards (scale + outline)
- Smooth transitions on all interactive elements
- Focus states for keyboard navigation

### Accessibility

- Semantic HTML5 structure
- Descriptive alt text on all images
- Proper heading hierarchy (h1, h2, h3)
- Keyboard-accessible navigation
- Focus indicators on interactive elements
- High contrast colors for readability

---

## 📝 Notes

### What's Included:

- ✅ Fully responsive HTML5/CSS3 website
- ✅ 10 travel destinations
- ✅ Interactive contact form
- ✅ Embedded YouTube video
- ✅ Social media integration
- ✅ Professional design and layout
- ✅ Accessibility features

### What's NOT Included:

- ❌ JavaScript functionality (optional, not evaluated)
- ❌ Backend database
- ❌ Form submission processing
- ❌ User authentication

---

## 🔗 Links

- **Live Website:** https://christianenogm.github.io/ExploreTheWorld/
- **GitHub Repository:** https://github.com/christianenogm/explore-the-world
- **Author:** [Christiane Nogueira Mendes](https://github.com/christianenogm)
- **Course:** Fanshawe College - Web Development and Internet Applications

---

## 🙏 Credits & Acknowledgments

- **Fonts:** Google Fonts (Dancing Script, Roboto)
- **Icons:** Font Awesome
- **Images:** Travel destination images sourced from various stock photo collections
- **Video:** YouTube travel video embed
- **Inspiration:** Modern travel booking websites and responsive design principles

---

## 📄 License

This project is created for educational purposes as part of the Web Development and Internet Applications course at Fanshawe College.

---

## 📞 Contact & Support

For questions about this project, contact:

- **Email:** c_nogueiramendes@fanshaweonline.ca
- **Phone:** 1-800-555-0199

---

**Made with ❤️ by Christiane Nogueira Mendes**

_"Travel is the only thing you buy that makes you richer." - Adventure awaits! ✈️🌍🏖️_
