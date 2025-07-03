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
   -[Common Issues Encountered & How They Were Fixed](#common-issues-encountered--how-they-were-fixed)
5. [Deployment](#deployment)
   - [deploying to GitHub Pages](#deploying-to-github-pages)
   - [Running this project locally](#running-this-project-locally)

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
- **W3C Markup Validation Service** to validate the HTML markup:  
  [https://validator.w3.org/](https://validator.w3.org/)

- **W3C CSS Validation Service** to check the CSS stylesheets:  
  [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)

### Common Issues Encountered & How They Were Fixed

- **Favicon Not Showing:**
  - *Issue:* The favicon did not appear in the browser tab after adding it.
  - *Fix:* Changed the href paths in the `<link>` tags to correctly point to the relative path of the favicon files inside the `assets/favicon/` folder.
  **Buggy code:**
<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">

- **Header Image Not Displaying:**
  - *Issue:* The header background image was not showing up.
  
  - *Fix:* Found a missing closing `</header>` tag that was causing rendering problems. Added the missing tag to fix the issue.
  <header>
  <div class="overlay">
    <h1>Site Title</h1>
    <p>Subtitle here</p>
  <!-- Missing </header> tag here -->

Fixed
<header>
  <div class="overlay">
    <h1>Site Title</h1>
    <p>Subtitle here</p>
  </div>
</header>
  
- **Audio Player Not Loading Audio:**
  - *Issue:* Some audio files did not play in the embedded audio player.
  - *Fix:* Checked file paths and filenames carefully to ensure they matched exactly, including the file extension and capitalization.

- **Navigation Menu Not Working on Small Screens:**
  - *Issue:* The hamburger menu toggle was not responding.
  - *Fix:* Verified that the checkbox input and label for the nav toggle had matching id and for attributes, and adjusted CSS display rules to enable the toggle.
  
  <input type="checkbox" id="nav-toggle" />
<label for="nav-toggle" class="nav-toggle-label">☰</label>
#nav-toggle:checked + .nav-toggle-label + nav {
  display: block;
}
- **Footer Social Media Icons Not Showing on Larger Screens**

On larger screen sizes, the social media icons in the footer were not displaying correctly. This was due to the footer height being too small, which caused the icons to be cut off or hidden.

**Issue:**  
The footer had a fixed height that was insufficient to show the icons properly.

**Fix:**  
Increased the footer height to `100px` to ensure enough space for the icons to display fully.

css
footer {
  height: 100px; }
 
## Deployment

This project was developed using **Visual Studio Code**, committed to Git, and pushed to **GitHub** using the built-in Git functionality within Cloud9.

### Deploying to GitHub Pages

To deploy this website from its GitHub repository to **GitHub Pages**, the following steps were taken:

1. Log into your GitHub account.
2. From your list of repositories, select the repository for this project.
3. Click on the **Settings** tab near the top of the page.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source**, click the dropdown menu labeled **None** and select **Master Branch** (or `main` branch if your repo uses that).
6. Upon selecting the branch, the page will refresh automatically, and the website will be deployed.
7. Scroll back to the **GitHub Pages** section to find the URL link to the live website.

> **Note:** At the time of submission, the Development and Master branches are identical.

### Running This Project Locally

To clone and run this project on your local machine:

1. Go to the project’s GitHub repository.
2. Click the green **Code** button (previously “Clone or download”).
3. Copy the URL under **Clone with HTTPS**.
4. Open your preferred terminal or command line interface.
5. Change the directory to where you want the project cloned:
   bash
   cd path/to/your/folder

   ### Credits

- **Content:**  
  The textual content, podcast descriptions, and overall narrative were thoughtfully created by the developer, who brings a unique interdisciplinary background combining applied chemistry, jazz music, and social science. This blend informs the exploration of Ethiopian traditional music, science, and societal themes featured throughout the website.

- **Media:**  
  The website’s visual assets, including the favicon and header images, were sourced and edited carefully:  
  - The original images were obtained from [Stockamba](https://stockamba.com/5798/kirar-%E1%8A%AD%E1%88%AB%E1%88%AD/), providing authentic Ethiopian cultural visuals.  
  - These images were then enhanced and customized using [Freepik’s](https://www.freepik.com/pikaso/assistant/v5ikXa47ye?image=32rQsbyREY&imageType=creation) free editing tools to better fit the website’s aesthetic and branding.  
  - Favicons were generated using [favicon.io](https://favicon.io/favicon-converter/), ensuring consistent and professional browser tab icons.

- **Code:**  
  The website’s codebase consists of HTML, CSS, and JavaScript developed within Visual Studio Code. The developer used the built-in Git integration for version control and pushed changes to GitHub. To ensure code quality and standards compliance, the developer utilized:  
  - [W3C Markup Validation Service](https://validator.w3.org/) to validate HTML.  
  - [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) to check CSS for errors and compatibility.  
  These tools helped maintain clean, accessible, and standards-compliant code throughout the project.

- **Acknowledgments:**  
  Special thanks to:  
  - **favicon.io** for providing simple and effective favicon generation tools.  
  - **W3Schools** for comprehensive and clear tutorials and references, especially on favicon implementation and responsive design.  
  - **GitHub** for hosting the project repository and enabling seamless deployment through GitHub Pages.  
  - **Google Fonts** for the beautiful and readable typography choices ('Lato' and 'Playfair Display') that enhance the user experience.  
  - The open-source community for creating tools and resources that supported the development and deployment of this website.
