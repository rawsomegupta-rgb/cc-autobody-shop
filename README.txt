
# C&C Autobody Shop Website

This is a simple multi-page static website for **C&C Autobody Shop**.

## Pages
- `index.html` → Home page (welcome and hero image)
- `our-work.html` → Gallery of projects
- `contact.html` → Contact form with EmailJS integration
- `style.css` → Shared stylesheet for all pages

## How to Use
1. Unzip the folder.
2. Open `index.html` in your browser to view the website.

## Adding Images
- Replace `car-restored-sample.jpg` in the Home page with your own image.
- Add your project images (e.g., `project1.jpg`, `project2.jpg`) into the same folder.
- Update `<img>` tags in `our-work.html` to match your image filenames.

## Setting Up EmailJS (Contact Form)
1. Create a free account at [EmailJS](https://www.emailjs.com/).
2. Create an **Email Service** (like Gmail or Outlook).
3. Create an **Email Template** with variables for name, email, and message.
4. Copy your **User ID**, **Service ID**, and **Template ID** from the EmailJS dashboard.
5. In `contact.html`, replace the placeholders:
   - `YOUR_USER_ID`
   - `YOUR_SERVICE_ID`
   - `YOUR_TEMPLATE_ID`

## Updating Phone Number
- In `contact.html`, replace `[Your Number Here]` with your real contact number.

---
© 2025 C&C Autobody Shop. All rights reserved.
