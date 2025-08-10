
Portfolio project (ready-to-deploy)
----------------------------------

What's included:
- index.html, about.html, services.html, contact.html, thankyou.html
- css/style.css
- js/script.js
- images/ (placeholder images you can replace)
- Instructions below

How to enable contact form (Formspree):
1. Create a free Formspree form at https://formspree.io and copy the form action URL (looks like https://formspree.io/f/xxxxx)
2. Open contact.html and replace the action value on the <form> element:
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   -> replace YOUR_FORM_ID with your form ID or full URL.
3. Optionally update the email address shown on the page.

Deploy suggestions:
- Drag & drop the project folder to Netlify, Vercel, or GitHub Pages to host it for free.
- Replace placeholder images in the images/ folder with your real photos (keep names or update src links).

Edit content:
- Replace "John Doe" and other placeholder text with your real name and info.
- Update social links in HTML to point to your profiles.

Enjoy! If you want, I can:
- Customize colors, fonts, or animations
- Add an email-send backend (Django example)
- Convert the project to a single-page app
