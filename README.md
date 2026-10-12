# TravelVista – Travel & Tourism Website

## 1. Project Overview

TravelVista is a travel and tourism website developed using HTML5 and CSS3. The website helps users explore popular destinations, view travel packages, discover famous tourist attractions, and access useful travel information.

It provides a clean, attractive, and user-friendly interface for planning trips.

## 2. Project Objectives

- To create an attractive travel and tourism website.
- To showcase popular tourist destinations in India.
- To display travel packages with prices and durations.
- To provide information about famous tourist attractions.
- To share travel tips and safety information.
- To create a contact form for travel enquiries.
- To implement responsive web design using CSS.

## 3. Technologies Used

- **HTML5:** Used to structure the website content.
- **CSS3:** Used to style the website and create layouts.
- **Flexbox:** Used to arrange destination cards, packages, and navigation links.
- **Media Queries:** Used to make the website responsive.
- **Unsplash:** Used to load destination and background images.

## 4. Main Features

### Home Section
- Website logo and navigation bar.
- Attractive background image.
- Welcome heading and introductory text.
- Explore Now button.

### Popular Destinations
- Goa
- Manali
- Jaipur

Each destination includes an image, a short description, and an Explore button.

### Travel Packages
- Goa Beach Package – ₹7,999 per person.
- Manali Adventure – ₹12,999 per person.
- Jaipur Heritage Tour – ₹8,999 per person.

Each package displays its duration, description, price, and Book Now link.

### Tourist Attractions
- Taj Mahal, Agra.
- India Gate, New Delhi.
- Hawa Mahal, Jaipur.

### Travel Information
- Travel tips.
- Important documents.
- Safety guidelines.

### Contact Section
- Full name input.
- Email address input.
- Destination selection.
- Message field.
- Submit Request button.

### Footer
- Website name.
- Website slogan.
- Copyright information.

## 5. HTML and CSS Implementation

**HTML implementation:**
- Semantic elements such as `<header>`, `<nav>`, `<section>`, `<form>`, and `<footer>`.
- Links for navigation between website sections.
- Images with alternative text.
- Form labels and input fields.

**CSS implementation:**
- Universal selector for resetting margins and padding.
- Flexbox for layouts.
- Background images and gradients.
- Colors, spacing, and typography.
- Rounded corners and box shadows.
- Hover effects and transitions.
- Media queries for smaller screens.

## 6. Project Structure

The combined project uses a single HTML file containing both HTML and CSS.

```text
TravelVista/
│
├── index.html
└── README.md
```

The CSS is written inside the `<style>` element in the `<head>` section of `index.html`. Therefore, a separate CSS file is not required.

## 7. How to Run the Project

1. Create a folder named `TravelVista`.
2. Open Notepad or Visual Studio Code.
3. Paste the complete HTML and CSS code.
4. Save the file as `index.html`.
5. Open the file in Google Chrome or another web browser.
6. Ensure an internet connection is available to load external images.

## 8. Responsive Design

The website uses the following media query:

```css
@media (max-width: 700px) {
    /* Mobile responsive styles */
}
```

This adjusts the navigation bar, headings, destination cards, package cards, and contact form for smaller screens.

## 9. Limitations

- The contact form is a demonstration and does not store or send user information.
- The Book Now links navigate to the contact section; they do not complete a booking.
- Package prices are sample values and may not reflect actual travel costs.
- External images require an internet connection.
- No backend database or payment gateway is connected.

## 10. Future Enhancements

- Add JavaScript for interactive functionality.
- Connect the contact form to a backend server.
- Implement actual travel booking functionality.
- Add destination search and filtering.
- Integrate secure online payment options.
- Add user login and registration.
- Display live travel information and updated package prices.

## 11. Conclusion

TravelVista demonstrates the use of HTML5 and CSS3 to develop a visually appealing travel and tourism website. It combines structured content, responsive layouts, destination cards, travel packages, tourist information, and a contact form into a single webpage.

The project provides practical experience in front-end web development and can be extended with JavaScript and backend technologies in the future.

**Project Name:** TravelVista

**Project Type:** Travel & Tourism Website

**Technologies:** HTML5 and CSS3

**Main File:** `index.html`

**Developed For:** Web Development Project
