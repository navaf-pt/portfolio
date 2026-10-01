# Cybersecurity Analyst Portfolio

A clean, modern, responsive personal portfolio website built with plain HTML, CSS, and vanilla JavaScript for a cybersecurity professional.

## Features

- Responsive dark cybersecurity-inspired design
- Sticky navigation with smooth scrolling
- Hero, About, Experience, Skills, Projects, Certifications, Education, and Contact sections
- Contact form that opens the user's email client
- Mobile-friendly layout
- Download resume button
- Lightweight static site with no frontend framework

## Project Files

- `index.html` — main page structure
- `style.css` — styling and responsive design
- `script.js` — interactivity, smooth scrolling, reveal effects, and mobile menu
- `assets/` — place your profile image and resume here

## Run Locally

You can open the site directly in a browser:

```bash
open index.html
```

Or serve it locally using Python:

```bash
cd /home/navaf/Projects/Portfolio
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Run with Docker

Build the Docker image:

```bash
docker build -t navaf-portfolio .
```

Run the container:

```bash
docker run -d -p 8080:80 --name navaf-portfolio navaf-portfolio
```

Then open:

```text
http://localhost:8080
```

To stop it:

```bash
docker stop navaf-portfolio
```

## Assets

Place your files in the `assets` folder:

- `assets/profile.jpg` — optional profile photo
- `assets/resume.pdf` — resume file for the download button

If the image is missing, the layout still looks complete and polished without it.

## Notes

- The GitHub and LinkedIn URLs can be updated directly in `index.html`.
- The contact form is frontend-only and opens the default mail client instead of submitting to a backend.
- This is intentionally kept lightweight and easy to edit.
# My-Portfolio
# My-Portfolio
