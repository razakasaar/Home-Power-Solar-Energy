# Home Power Solar Energy — Website

Static 4-page showcase site: Home, Products, About Us, Contact Us.

## Structure

```
index.html        Home page
products.html      Product listing (PV11000 inverter + solar panel packages)
about.html          About Us (placeholder content, ready to fill in)
contact.html        Contact form + contact details (placeholder details)
css/style.css        Shared styles (brand green sampled from client logo: #A8CF46)
js/main.js            Mobile nav toggle + basic contact form handling
assets/images/         Logo + product images
```

## Status / what's still needed from the client

- [ ] Real phone number, email, address, business hours (currently placeholders)
- [ ] Prices for PV11000 and solar panel packages (currently "Contact for price")
- [ ] Additional products (batteries, on-grid systems, complete systems — specs + photos)
- [ ] About Us content: company story, years in business, certifications, team
- [ ] Social media links
- [ ] Real map location (Google Maps embed)
- [ ] Contact form backend (currently front-end only, no email sending configured)

## Notes

- Logo and one product photo (PV11000) were extracted from the client's supplied marketing banner image and saved under `assets/images/`.
- Brand green (`#A8CF46`) was sampled directly from the client's logo/banner for consistency.
- No build step — plain HTML/CSS/JS. Open `index.html` in a browser, or serve the folder with any static file server.
