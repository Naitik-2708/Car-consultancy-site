🚗 Toyota Purnea – Car Dealership Website

A modern, responsive car dealership website built to showcase vehicles, provide downloadable brochures, collect customer reviews, and highlight a dedicated sales officer.

📌 Overview

This project is a front-end web application designed for a car dealership (Toyota Purnea). It allows users to:

Explore available cars
View/download car brochures (PDF)
Submit enquiries
Leave reviews with ratings
View salesperson profile (Mihir – Sales Officer)

The goal is to provide a smooth and professional digital experience for customers.

 Features
🚘 1. Car Listing Section
Displays multiple vehicles with:
Image
Specifications
Price
Each car includes:
Enquiry button
Brochure button (PDF support)
📄 2. Brochure System
Users can click on “Brochure” to:
Open PDF in a new tab
Each car has its own brochure file
Fallback alert if brochure is unavailable
🧾 3. Enquiry Popup
Triggered from multiple buttons
Collects:
Name
Phone number
Address
Message
Data is sent to Google Sheets (via Apps Script API)
⭐ 4. Review System
Floating review panel (slides from right side)
Users can submit:
Name
Address
Star rating (1–5)
Review message
Behavior:
Reviews are:
Added dynamically to UI
Stored in localStorage
Persist after page reload
🔁 5. Review Marquee
Reviews scroll continuously (horizontal animation)
Smooth infinite loop effect
New reviews are appended live
👤 6. Salesperson Section (Mihir)
Dedicated front-page profile
Includes:
Name: Mujahid Ali (Mihir)
Role: Sales Officer
Contact details
Business branding (Toyota Purnea)
Builds trust and personal connection with customers
🛠️ Tech Stack
HTML5
CSS3
Vanilla JavaScript
Google Apps Script (for form backend)
LocalStorage (for reviews)
📂 Project Structure
project/
│
├── index.html
├── style.css
├── script.js
│
├── pics/              # Images
├── brochures/         # PDF files
│
└── README.md
⚙️ Setup Instructions
Clone the repository:
git clone https://github.com/your-username/project-name.git
Open the project folder:
cd project-name
Run the project:
Open index.html in your browser

 Brochure Setup

Place PDF files inside:
Example:

brochures/fortuner.pdf
brochures/hilux.pdf

Make sure the file names match the JavaScript mapping.

🧠 Key Functional Logic
Brochure Mapping
const brochureLinks = {
  fortuner: "brochures/fortuner.pdf",
  hilux: "brochures/hilux.pdf"
};
Review Storage
Stored using:
localStorage → "toyotaPurneaReviews"
Form Submission
Uses Google Apps Script API
Sends data via fetch()
🚨 Known Issues (Be Honest)
Some UI elements may need polishing on small screens
No backend database (reviews stored only locally)
Brochure availability depends on uploaded PDFs
No authentication system
🚀 Future Improvements
Admin dashboard for managing reviews
Real database (Firebase / MongoDB)
Search & filter for cars
WhatsApp integration
Booking test drives
Dark mode
👨‍💼 Author / Client

Mujahid Ali (Mihir)
Sales Officer – Toyota Purnea

📞 9031021458 / 9955003705
📧 SM@PRAKASHTOYOTA.COM
📍 NH-31 Barsauni, Purnea, Bihar

📜 License

This project is for educational and business use.
You can modify and reuse with proper attribution.# Car-consultancy-site
