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

https://akshairs-portfolio.netlify.app/
