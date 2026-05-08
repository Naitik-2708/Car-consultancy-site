Toyota Purnea – Digital Car Consultancy Platform

A responsive dealership web application built for Toyota Purnea to help customers explore vehicles, download brochures, submit enquiries, and share ownership experiences through a live review system.

This project was developed to bridge the gap between showroom interaction and digital customer engagement.

Live Project

Add deployment link here:

https://your-live-demo-link.com

Project Overview

The platform provides a digital showroom experience where visitors can:

Browse available Toyota vehicles
View specifications and pricing
Download official brochures
Submit sales enquiries directly
Read and post customer reviews
Connect with a dedicated sales officer

The focus was to create a clean, trust-driven interface with minimal friction for customers.

Core Features
Vehicle Showcase

Customers can browse multiple vehicles with:

High-quality vehicle images
Key specifications
Pricing details
Quick enquiry option
Brochure download support
PDF Brochure Integration

Each vehicle can have its own brochure.

Features:

Opens brochure in a new tab
Dedicated PDF mapping for each car
Graceful fallback if brochure is unavailable

Example:

const brochureLinks = {
  fortuner: "brochures/fortuner.pdf",
  hilux: "brochures/hilux.pdf"
};
Enquiry System

Users can submit dealership enquiries through a popup form.

Collected data:

Full name
Phone number
Address
Message

Form submissions are pushed to Google Sheets using Google Apps Script.

Customer Review System

Visitors can submit:

Name
Location
Star rating
Review message

Features:

Reviews appear instantly in UI
Stored using browser local storage
Persist after page refresh

Storage key:

toyotaPurneaReviews
Live Review Marquee

Customer reviews continuously scroll across the interface using an infinite animation loop, helping create social proof and engagement.

Sales Officer Profile

A dedicated trust-building section featuring:

Mujahid Ali (Mihir)
Sales Officer – Toyota Purnea

Includes:

Contact information
Branding details
Dealership location
Tech Stack

Frontend:

HTML5
CSS3
Vanilla JavaScript

Client-side Storage:

LocalStorage

External Integration:

Google Apps Script
Google Sheets API
Project Structure
project/
│
├── index.html
├── style.css
├── script.js
│
├── pics/
├── brochures/
│
└── README.md
Getting Started

Clone the repository:

git clone https://github.com/your-username/project-name.git

Move into the project directory:

cd project-name

Run locally:

Open index.html in your browser.

Current Limitations

Being transparent:

Reviews are stored locally, not in a central database
No authentication or admin moderation
Some UI components need further mobile optimization
Brochure availability depends on uploaded PDF files
Planned Improvements

Future roadmap:

Admin dashboard
Firebase or MongoDB integration
Vehicle search and filtering
WhatsApp enquiry integration
Test-drive booking
Dark mode
Project Owner

Mujahid Ali (Mihir)
Sales Officer – Toyota Purnea

Phone: +91 9031021458
Phone: +91 9955003705
Email: SM@PRAKASHTOYOTA.COM

Location: NH-31, Barsauni, Purnea, Bihar

License

This project is intended for educational, portfolio, and business demonstration purposes.

