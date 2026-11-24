# VIQ Auto's

A multi-page car dealership website for VIQ Auto's, a seller of quality pre-owned vehicles in Lagos, Nigeria.

## Brands
Toyota, Lexus, Mercedes-Benz, Changan Motors and Jetour. Toyota and Lexus cars are pre-owned. Mercedes-Benz, Changan and Jetour cars are brand new, with indicative prices (estimates, to be confirmed with suppliers) and "Photo coming soon" placeholders until real photos are added.

## Pages
- **Home** - hero with featured cars, shop by brand, why choose us, how it works, test drive call-to-action
- **About Us** - our story, mission, vision and values
- **Our Products** - car listings with prices, spec tags, brand filter and a WhatsApp enquiry button on every car
- **Book a Test Drive** - test drive booking form (design only for now)
- **Contact Us** - contact details and message form (design only for now)

## Features
- Responsive layout for phones, tablets and desktops
- One shared stylesheet (`site.css`) so every page looks consistent. Colours and fonts are set in the `:root` block at the top.
- Sticky navigation with a mobile menu
- Floating WhatsApp button on every page
- Brand filter on the products page
- "Enquire on WhatsApp" buttons that open a chat with the car name and price already filled in
- Full car descriptions available under "View full details"

## Built With
- HTML5
- CSS3 (Flexbox, Grid, custom properties, media queries)
- Vanilla JavaScript (mobile menu, brand filter, WhatsApp links)
- Font Awesome icons and Google Fonts (Sora, Inter)

## Project Structure
```
index.html        Home page
about.html        About Us
products.html     Our Products
testdrive.html    Book a Test Drive
contact.html      Contact Us
site.css          Shared styles for all pages
assets/           Logo and site images
```
The older stylesheets (`style.css`, `products.css`, `about.css`, `contact.css`, `testdrive.css`) are no longer used and can be deleted.

## Running Locally
No build step is needed. Open `index.html` in a browser, or use the Live Server extension in VS Code.

## Status
In development. Still to do:
- Confirm the Mercedes-Benz, Changan and Jetour prices with suppliers and add real photos of those cars
- Make the test drive and contact forms send enquiries
- Replace hotlinked car photos with our own photos in `assets/`
- Add our own hero photo
- Add more JavaScript features (search, sorting, car detail pages)

## Author
Etong Victor Martins
