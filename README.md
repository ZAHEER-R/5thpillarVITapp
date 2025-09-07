# 5thpillarVITapp

# README for 5th Pillar VIT Website

## Project Overview
This is the official website for **5th Pillar VIT**, a student-led chapter at Vellore Institute of Technology (VIT), Vellore, Tamil Nadu, India. The organization is dedicated to strengthening democracy through education, anti-corruption initiatives, and civic engagement. As a non-profit student society, 5th Pillar VIT aims to empower youth to become responsible, patriotic citizens by promoting awareness of laws, ethical practices, and social responsibilities.

The website serves as a platform to showcase the club's activities, events, resources, and ways to get involved. It is built with HTML, CSS, and JavaScript, focusing on responsive design for desktop, tablet, and mobile views.

Key Mission: Encourage, enable, and empower every citizen of India to eliminate corruption at all levels of society while fostering democratic values through education and community programs.

## Features
- **Navigation Menu**: Responsive menu with dropdowns for sections like About Us, Events, Committees, Blog, Collaborators, Gallery, Outreach, Contact, and Resources.
- **Hero Sections**: Dynamic banners highlighting club initiatives.
- **Forms**: Interactive forms for event registration, club membership, feedback, and partnership inquiries.
- **Gallery and Media**: Photo albums, videos, and moments from events.
- **Footer**: Quick links, social media integration (Instagram, Facebook, LinkedIn), and contact information.
- **Popup on Load**: Optional popup card for announcements (can be closed and remembered via localStorage).
- **Responsive Design**: Adapts to mobile, tablet, and desktop screens using media queries.
- **Form Validation**: Client-side validation with alerts for required fields; integration with Google Sheets for data submission (using Google Apps Script).
- **Anti-Corruption Focus**: Educational resources on legal awareness, FAQs, and anti-bribery programs.

## Technologies Used

- **HTML5**: Structure and semantics.
- **CSS3**: Styling, including variables, flexbox, grid, and media queries for responsiveness.
- **JavaScript**: Interactivity, form handling, popup logic, localStorage for user preferences, and API calls (e.g., to Google Sheets).
- **Font Awesome**: Icons for navigation and social links.
- **SweetAlert2**: For user-friendly alerts on form submission.
- **External Libraries**: None beyond CDNs for icons and alerts.

## Installation/Setup
1. **Clone or Download**: Download the project files from the repository or local directory (e.g., `C:/Users/z4pro/OneDrive/Desktop/5p/public/`).
2. **Local Server**: Open `index.html` in a browser, or use a local server like Live Server in VS Code for better testing.
3. **Dependencies**: No installation required, but ensure internet access for CDNs (Font Awesome, SweetAlert2).
4. **Google Sheets Integration**:
   - Set up a Google Sheet and deploy a Google Apps Script web app.
   - Update the `scriptURL` in the JS code with your deployed script URL.
   - Example Script URL: 'https://script.google.com/macros/s/[YOUR_SCRIPT_ID]/exec'.

## Usage
- **Navigation**: Click the menu icon on mobile/tablet to open the sidebar; hover/click dropdowns for submenus.
- **Forms**: Fill in details and submit; validation ensures required fields are completed. Data is sent to Google Sheets.
- **Popup**: Appears on first load; close it once, and it won't show again (uses localStorage).
- **Customization**: Edit HTML for content, CSS for styles, and JS for logic (e.g., adjust popup behavior).

To test responsiveness:
- Mobile: Resize browser to < 480px.
- Tablet: 481px–768px.
- Desktop: > 769px.

## Folder Structure
- **public/**: Main website folder.
  - `index.html`: Home page.
  - Subfolders: `about/`, `events/`, `committees/`, `blog/`, `collaborators/`, `gallery/`, `outreach/`, `get-involved/`, `resources/` (for respective pages).
  - `Images/`: Assets like logos and photos.
- **Styles**: Embedded in HTML or separate CSS files.
- **Scripts**: Embedded JS for interactivity.

## Contributing
- This is a student project for 5th Pillar VIT. Contributions welcome for bug fixes, features, or design improvements.
- Contact: Reach out via the website's contact form or email (e.g., fifthpillar2023@gmail.com).
- Developers: Fork the repo, make changes, and submit a pull request.

## License
This project is open-source under the MIT License. Feel free to use, modify, and distribute for educational purposes. Copyright © 2025 5th Pillar VIT. All rights reserved.

For more info, visit the live site (if hosted) or contact the club at VIT Vellore.

