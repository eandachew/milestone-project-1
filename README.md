# The Sound of Etiele  
![Banner](../milestone-project-1/assets/images/podcast-banner.jpg)  
*Watermark: "Development Preview - Unauthorized use prohibited"*

## Table of Contents
1. [UX Design](#ux-design)
   - [Project overview](#project-overview)
   - [Project Goals](#project-goals)
   - [Business Objectives](#business-objectives)
   - [Design system](#design-system)
   - [Wireframe](#wireframe)

2. [Features](#features)
   - [Existing Features](#existing-features)
   - [Features Left to Implement](#features-left-to-implement)
   
3. [Technologies Used](#technologies-used)
4. [Testing](#testing)
5. [Deployment](#deployment)
6. [Credits](#credits)
   - [Content](#content)
   - [Media](#media)
   - [Code](#code)
   - [Acknowledgments](#acknowledgments)

---

## UX Design
### project overview
- This project aims to create a responsive and visually engaging landing page for a podcast series that educates and entertains users on topics at the intersection of art and science.

### Project Goals
- Provide a clean, focused user interface that works well on all screen sizes.
- Use visual design to emphasize sound, rhythm, and learning.
- Present an easy way to listen to the latest podcast episode.
- Create a strong brand identity for "The Sound of Etiele."

### Business Objectives

- Attract and retain listeners through professional design and clear messaging.
- Grow user engagement and episode reach.
- Lay groundwork for future monetization (sponsorship, memberships, etc.).

### Design system

This website, **The Sound of Etiele**, was designed with a focus on accessibility, simplicity, and storytelling to reflect the interdisciplinary themes of music, science, and society. Below are the key design choices and the reasoning behind them:

### 1. Typography
- **Fonts Used**:
  - `'Lato'` for general body text — modern, clean, and easy to read.
  - `'Playfair Display'` for the logo — adds elegance and artistic character.
- **Source**: Both fonts were imported from [Google Fonts](https://fonts.google.com/).

### 2. Color Scheme
- **Backgrounds**:
  - White and light gray (`#f9f9f9`) used to keep the design clean and minimalist.
  - Footer uses a rich brown (`#211702`) for warmth and depth.
- **Accent Color**:
  - A soft red-orange (`#ff6f61`) was used for call-to-action buttons to attract attention without being too harsh.

### 3. Layout & Structure
- Clear **Header → Main → Footer** layout for intuitive navigation.
- Content is centered and constrained with `max-width: 800px` for readability.
- Flexbox was used to create responsive layout and vertical spacing.

### 4. Imagery & Media
- **Header and background images** reflect the musical and cultural theme.
- **Audio players** are embedded for episode playback.
- **Favicon**:
  - Created using [favicon.io](https://favicon.io/favicon-converter/).
  - Image sourced from [Stockamba](https://stockamba.com/5798/kirar-%E1%8A%AD%E1%88%AB%E1%88%AD/).
  - Edited using [Freepik’s AI editor](https://www.freepik.com/pikaso/assistant/v5ikXa47ye?image=32rQsbyREY&imageType=creation).
  - Path updated in HTML based on [W3Schools favicon guide](https://www.w3schools.com/html/html_favicon.asp).

### 5. Navigation
- **Mobile-first approach**:
  - A checkbox + label combo creates a responsive hamburger menu for small screens.
  - Navigation switches to a horizontal layout on larger screens (using media queries).
  
### 6. Accessibility & SEO
- Semantic HTML tags: `<main>`, `<section>`, `<nav>`, `<footer>` for better accessibility and structure.
- **Meta tags** added for improved SEO:
  - `description` and `keywords` to enhance visibility in search engines.
- Descriptive `aria-label`s for social media links.

### 7. CSS & Styling
- CSS reset using wildcard `*` to eliminate inconsistent browser styles.
- Custom styling for:
  - Header overlay
  - CTA buttons
  - Episode cards
  - Footer background with image and gradient overlay
- Internal file structure:
  - CSS stored in `assets/css/style.css`
  - Audio in `assets/audio/`
  - Images and favicon in organized `assets/images/` and `assets/favicon/`

### 8. Media Queries
- Added a media query for screens `768px` and wider.
  - Navigation becomes horizontal.
  - Improved spacing and visibility for larger screens.

### 9. Icons
- Integrated [Font Awesome](https://fontawesome.com/) for clean, scalable social media icons.
- Positioned in the footer with even spacing and consistent color.

## Wireframe

Here is the wireframe for the project:

![Wireframe](../milestone-project-1/assets/images/wireframe.png)

- Header

Banner image + "The Sound of Etiele" text

Subtitle: "Where music and society intersect"

- Main

Heading: "Listen. Learn. Connect."

Paragraph + CTA button ("🎧 Listen")

- Mobile Nav

☰ Toggle → Home | Episodes | About | Contact

- Layout

Mobile: Stacked

Desktop: Full-width   

## Features

### Existing Features
- Responsive layout optimized for mobile and desktop.
- Embedded audio player for podcast episodes.
- Hamburger menu for easy navigation on smaller screens.
- SEO-friendly meta tags for better search engine visibility.
- Custom favicon and branding consistent throughout the site.
- Social media links integrated with Font Awesome icons.
- Clean and accessible design using semantic HTML and CSS reset.

### Features Left to Implement
- User login and personalized playlists.
- Search functionality for episodes and articles.
- Interactive community forum or comment section.
- Support for multiple languages beyond Amharic and English.
- Enhanced accessibility features (e.g., keyboard navigation improvements).
- Automated deployment and continuous integration setup.

## Technologies Used

- **HTML5** — Semantic markup for page structure.
- **CSS3** — Styling, layout, and responsive design.
- **Google Fonts** — Typography (`Lato`, `Playfair Display`).
- **Font Awesome** — Iconography for social media links.
- **Visual Studio Code** — Code editor and development environment.
- **Git & GitHub** — Version control and remote repository hosting.
- **Freepik** — For editing and enhancing images used on the website.
- **favicon.io** — For generating and converting the favicon icons.

## Testing

- Tested across multiple browsers (Chrome, Firefox, Edge) to ensure compatibility.
- Responsive design verified on different screen sizes using browser dev tools.
- Audio playback functionality tested on desktop and mobile devices.
- Accessibility checks performed for semantic HTML and keyboard navigation.
- SEO meta tags verified with online tools for proper indexing.
