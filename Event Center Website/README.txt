=========================================================
 Temple Stadium Website
=========================================================

Overview
--------
This is a multi-page static HTML/CSS website for "Temple Stadium" – a fictional sports and entertainment venue.  
The site provides visitors with general information, upcoming events, the concessions menu, location details, and a contact form.

Pages
-----
1. Homepage.html
   - Overview of Temple Stadium and its offerings.
   - Navigation menu linking to all other sections.
   - A list of amenities and highlights.

2. Eventspage.html
   - List of upcoming events with event names, dates, and descriptions.
   - Styled event list layout.

3. Menupage.html
   - Concessions menu categorized into Stadium Classics, Burgers & Sandwiches, Pizza & Specialty Items, Beverages, and Desserts.
   - Uses a CSS grid layout for menu categories.

4. Locationpage.html
   - Address, hours, parking, public transit, accessibility features, guest services, and contact details.
   - Embedded stadium map image with captions.

5. Contactuspage.html
   - Contact phone number and a form for visitors to send inquiries.
   - Form fields include name, phone, email, country, age, and a comment box.
   - Reset and submit buttons provided.

6. styles.css
   - Global styles, including page background, typography, and grid layouts.
   - Specific styling for navigation menus, events list, offerings list, menu page layout, contact form, and location map.
   - Responsive element: map width uses `clamp()` to adjust for different viewport sizes.

Navigation
----------
Each HTML page contains a consistent navigation menu:
- Home
- Events
- Menu
- Location
- Contact

How to View
-----------
1. Place all HTML files and `styles.css` in the same folder.
2. Open `Homepage.html` in a web browser.
3. Navigate between pages using the menu links.

Customization
-------------
- Background image URL and colors can be changed in `styles.css`.
- Event details, menu items, and contact info can be updated directly in the corresponding HTML files.
- Ensure linked file names remain consistent to maintain navigation functionality.

Notes
-----
- This site is static and does not include backend functionality. The contact form will require server-side handling (e.g., PHP, Node.js) to actually process submissions.
- For best results, host files on a web server or use a local development environment.

=========================================================
