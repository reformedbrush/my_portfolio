# Akshai R Sangeeth — portfolio

Static personal site for graduate, internship, and junior software and security applications. It is HTML, CSS, and JavaScript. There is no package install and no build step.

Published at [akshairs-portfolio.netlify.app](https://akshairs-portfolio.netlify.app/).

## Run locally

From this folder:

```bash
python3 -m http.server 8765
```

Open `http://127.0.0.1:8765/`.

## Deploy

Netlify publishes the repository root (`netlify.toml` sets `publish = "."`). Push to the connected branch and Netlify will update the existing site. Do not add a build command unless you introduce a bundler.

## Edit with care

- Resume file: `assets/ars-cv.pdf`
- Profile photo: `assets/profile.png`
- Project facts are written in `index.html`. Only add a feature if it is in the repository you link.
- Message Service and the security risk assessment are labelled placeholders. Planned labs are labelled not built.
- The Bachelor institution name is still blank because the previous site did not include it.
- Master's dates are 2025–Present and should be checked against enrolment.
