# Dr. Lauren Dagan Amoss — GitHub Pages Website

This is a simple static website for GitHub Pages.

## Files included

- index.html
- style.css
- profile.jpg
- README.md

## Important upload instruction

Upload the files themselves to GitHub.

Do not upload only the ZIP file.
Do not upload only the folder.

The file `index.html` must appear in the main/root area of the repository.
The file `profile.jpg` must be in the same place as `index.html`.

## Hebrew button

The site includes a Hebrew button in the hero section and navigation.
It leads to a short Hebrew section inside the same page.

## Contact form setup

The website includes a contact form, but GitHub Pages cannot send emails by itself because it has no backend.

To make the form work:

1. Go to https://formspree.io
2. Create a free account.
3. Create a new form.
4. Formspree will give you an endpoint that looks like:
   https://formspree.io/f/abcdxyz
5. Open `index.html`.
6. Find this line:

   <form class="contact-form" action="https://formspree.io/f/your-form-id" method="POST">

7. Replace:
   https://formspree.io/f/your-form-id

   with your real Formspree endpoint.

8. Save the file and upload it again to GitHub.

Your email will not appear publicly on the website.

## How to activate GitHub Pages

1. Go to your GitHub repository.
2. Go to Settings.
3. Go to Pages.
4. Under Source, choose Deploy from a branch.
5. Under Branch, choose main.
6. Choose /root.
7. Click Save.

## Editing

Edit text in `index.html`.
Edit colors and design in `style.css`.
Replace `profile.jpg` if you want to use a different photo later.
