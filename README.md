 # EGIT
 Emmanuel Global Institute of Technology — Student Registration Form
A responsive HTML admission registration form for academic institutions. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks or external libraries required. Just open index.html in any modern browser and it works out of the box.
Features
Animated background with floating orbs, twinkling stars, and flying paper planes
Smooth entrance animations on the card, fields, and section labels
Live progress bar that tracks form completion as the user types
Responsive grid layout that adapts from desktop down to mobile
Styled pill radio buttons for gender selection
File upload zones for passport photo and academic certificates
Submit button turns green with a checkmark on successful submission
No build tools, no npm, no dependencies — a single self-contained HTML file
Form Sections
Personal Information — First name, last name, date of birth, nationality, NIN/ID number, gender
Contact Details — Email address, phone number, residential address
Academic Information — Programme applied for, degree level, previous school, graduation year
Document Upload — Passport photo (JPG/PNG), academic certificates (PDF/JPG)
Emergency Contact — Guardian or parent name and phone number
Getting Started
Clone or download the repository, then open the file directly in your browser:
Code
No installation or server needed. All styles and scripts are embedded inside index.html for portability.
Customization
To change the institution name, find and replace "Emmanuel Global Institute of Technology" inside index.html.
To add or remove programmes, edit the <select> dropdown under the Academic Information section and add or delete <option> tags as needed.
To change the color scheme, update the CSS variables at the top of the <style> block. The primary colors used are navy #0a1f44, royal blue #1a4fcf, and sky blue #3b82f6. Headings use Playfair Display and body text uses DM Sans, both loaded from Google Fonts.
To connect a real backend, replace the submit event listener with a fetch POST call to your API endpoint, passing a FormData object built from the form.
Browser Support
Works on Chrome 90+, Firefox 88+, Safari 14+, and Edge 90+.
License
Open source under the MIT License. Free to use, modify, and distribute.
