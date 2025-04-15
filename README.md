### Project Overview

The provided code is a modern, responsive “Contact Us” webpage that integrates advanced styling features, dark mode functionality, and interactive UI elements. The page is built with HTML, CSS, and vanilla JavaScript and is designed to be visually appealing and user-friendly, making it ideal for businesses or personal projects that aim to enhance user engagement and communication.

---

### Key Features

#### 1. **Responsive Design & Layout**

- **Container and Grid System:**  
  The layout is wrapped in a `.container` class with a maximum width of 1200px, ensuring that the content remains centered and well-spaced on larger screens while using padding to create breathing room.  
  Sections such as the "When and Why to Contact Us" and "Our Services" utilize CSS Grid (`.cards`) to automatically adapt the number of columns based on the viewport size.  
- **Flexbox for Form Sections:**  
  The contact form is split into two sections (contact details and the form itself) using Flexbox. The `.form-section` ensures that the two panels wrap gracefully on smaller screens, thanks to flex-wrap and media queries.
- **Media Queries:**  
  Responsive breakpoints adjust font sizes, grid layouts, and overall spacing. For example, header fonts and paragraph paddings are scaled down for devices with a maximum width of 768px.

#### 2. **Modern Styling and Visual Effects**

- **Custom Fonts and Icons:**  
  The project utilizes the "Exo" font from Google Fonts for a sleek, modern appearance. Material Icons are used to visually represent different contact options and services throughout the page.
- **CSS Variables:**  
  A series of CSS custom properties (variables) are defined under `:root` to manage theme colors, button styles, shadows, and transition times. This makes the code modular and easier to maintain or extend.
- **Dark Mode Implementation:**  
  A dark theme is seamlessly integrated by toggling a `dark` class on the `<body>` element. When active, the code swaps out the CSS variables (such as background color, text color, card background, and shadow intensity) to present a dark mode version.
- **Smooth Animations and Transitions:**  
  - A keyframe animation (`fadeIn`) provides a subtle fade-in effect when the page loads.  
  - Button interactions and form focus states include smooth transitions for color changes, border highlights, and box shadows.
- **Custom Scrollbar:**  
  Custom styling for the scrollbar is implemented using `::-webkit-scrollbar` selectors, which visually complement the overall theme by matching the button and card color schemes.

#### 3. **Interactive UI Elements**

- **Dark Mode Toggle Button:**  
  A floating button positioned at the bottom-right corner toggles between dark and light modes. This button uses Material Icons to visually indicate the current theme (e.g., `dark_mode` for light mode and `light_mode` for dark mode). The toggle functionality is handled via JavaScript.
- **Card-Based Sections:**  
  The page features several sections with card layouts:
  - **"When and Why to Contact Us" Cards:**  
    Eight cards present various reasons for contacting, each with a unique icon, title, and brief description.
  - **"Our Services" Cards:**  
    Additional cards outline the key services provided, ensuring that users can quickly grasp what is offered.
- **Contact Information and Form:**  
  - The left panel of the form section lists contact details, including emails, phone numbers, call times, and response times. This organized structure builds trust by showing professional support details.
  - The right panel contains an interactive contact form, which uses clear input fields and placeholders to guide users. It collects the user’s name, email, phone, and message.

#### 4. **Code Quality and Maintainability**

- **Semantic HTML Structure:**  
  The code uses appropriate semantic HTML elements such as `<header>`, `<section>`, and `<form>` to improve accessibility and SEO.
- **Clean and Modular CSS:**  
  By leveraging CSS variables and modern selectors, the stylesheet is both efficient and easy to update. The use of transition properties enhances user experience without complicating the code.
- **Minimal JavaScript for Dynamic Behavior:**  
  The JavaScript is focused solely on toggling the dark/light mode. It listens for click events on the toggle button, applies/removes the `dark` class on the `<body>`, and updates the icon accordingly.
- **Accessibility and Usability Considerations:**  
  - Clear and legible typography with high contrast between text and background colors.  
  - Sufficient touch targets for interactive elements like buttons, ensuring compatibility on mobile devices.
- **Customizable Design:**  
  The overall design allows easy modifications. Developers can adjust CSS variables to change the theme, or add new cards and form fields without restructuring the entire layout.

---

### Conclusion

This project exemplifies modern web development practices by combining responsive design, interactive UI elements, and a user-centric layout. The clear separation between contact information and form inputs enhances usability, while the dark mode toggle enriches the overall user experience. Whether you’re launching a business website or creating an interactive portfolio, this code offers a robust starting point for building an engaging “Contact Us” page.

### Images
![image](https://github.com/user-attachments/assets/4e891e02-8d49-4248-a572-53a39b3d3e5e)
![image](https://github.com/user-attachments/assets/948a3008-c20c-42f3-8ff8-a871b52eaec2)
