# Dr. Syed Muhammad Abbas Rizvi - Portfolio Website

A professional and futuristic portfolio website for Dr. Syed Muhammad Abbas Rizvi, an educationalist, creative writer, and content creator.

## Features

- Responsive design that works on all devices
- Professional and futuristic UI/UX
- Dark/Light theme toggle for user preference
- Interactive elements with smooth animations
- Contact form that sends emails directly to Dr. Rizvi's inbox
- Sections for About, Education, Publications, and Contact information

## Setup Instructions

### 1. Basic Setup

Simply open the `index.html` file in a web browser to view the website locally.

### 2. Email Functionality Setup

The contact form is configured to use EmailJS to send emails directly to Dr. Rizvi's inbox. To set this up:

1. Create an account at [EmailJS](https://www.emailjs.com/)
2. Create a new email service in your EmailJS dashboard
3. Create an email template with the following template parameters:
   - `from_name`: Sender's name
   - `from_email`: Sender's email
   - `subject`: Email subject
   - `message`: Email message content
   - `to_email`: Recipient's email (already set to smarcreations1@gmail.com)
4. Get your EmailJS User ID, Service ID, and Template ID
5. Update the following in the code:
   - In `index.html`: Replace `YOUR_USER_ID` with your actual EmailJS User ID
   - In `js/script.js`: Replace `'service_id'` with your actual Service ID and `'template_id'` with your actual Template ID

## File Structure

```
├── assets/
│   └── profile.svg       # Profile image
├── css/
│   └── style.css         # Main stylesheet
├── js/
│   └── script.js         # JavaScript functionality
├── index.html            # Main HTML file
└── README.md             # This file
```

## Contact Information

Dr. Syed Muhammad Abbas Rizvi
- Email: smarcreations1@gmail.com
- Phone: +92 311 4512514
- Location: Lahore, Pakistan

## License

All rights reserved. This website is the property of Dr. Syed Muhammad Abbas Rizvi.