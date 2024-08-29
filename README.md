# html-mini-site
# HTML Beginner Exercise 

This project demonstrates a simple HTML website that includes a contact form to send emails using the EmailJS service. It contains a basic layout with a heading, a list of familiar technologies, a list of technologies to learn, useful links, and a form for contacting the developer. 

## Table of Contents
- Technologies Used
- Features
- EmailJS Integration 
- How to Run the Project
- Form Configuration
- Contact Information

## Technologies Used
- HTML5
- CSS3
- JavaScript
- [EmailJS](https://www.emailjs.com/) (For email functionality)

## Features
1. **Unordered List of Familiar Technologies**: JavaScript, HTML5, CSS, Java.
2. **Ordered List of Technologies to Learn**: Ruby, Python, NextJS, Tailwind.
3. **Hyperlinks**: Links to Google, Wikipedia, and GitHub.
4. **Email Form**: Users can send an email to the developer using the contact form. The form utilizes EmailJS to send emails without needing a backend server.
5. **Basic Text Formatting**: Usage of bold and italic text for emphasis.

## EmailJS Integration
The form in this project uses EmailJS, a service that allows sending emails directly from the client-side using JavaScript. The following steps describe how to set up the EmailJS integration.

1. **EmailJS Initialization**: 
   - The EmailJS service is initialized in the JavaScript code using the following:
     ```javascript
     emailjs.init("YOUR PUBLC KEY");
     ```

2. **Sending Emails**:
   - When the form is submitted, the user’s input (name, email, and message) is sent to the configured EmailJS service using the `emailjs.send` method.

3. **EmailJS Configuration**:
   - Service ID: `YOUR SERVICE ID`
   - Template ID: `YOUR TEMPLATE ID`
   - Public Key: `YOUR PUBLIC KEY`

   These values must be configured in your EmailJS account to work correctly. 

## How to Run the Project

1. **Clone or Download the Project**:
   - Clone the repository to your local machine or download the ZIP file and extract it.

   ```bash
   git clone https://github.com/yourusername/html-beginner-exercise.git
