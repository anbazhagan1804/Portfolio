# Anbazhagan M — Portfolio

A single-page portfolio for Network, DevOps, Cloud, and IT Support roles. Live at **https://anbazhagan1804.github.io/Portfolio/**.

## Sections
- Hero: role tagline, call-to-action buttons.
- About: background, stats, and meta details.
- Services: networking, observability, cloud & DevOps, containerization, automation.
- Projects: GitOps pipeline, ML-driven auto-scaling, multi-cloud DR, DevSecOps, observability stack, chatops, serverless, self-healing infra, OpenCV crack detection, and home lab highlight.
- Education & Certifications: B.E. ECE (Aug 2022–Jun 2026) and Cisco Network Technician (Aug 2025).
- Resume downloads: four tailored PDFs (Network, DevOps, IT Support, Cloud) in `/Resume/` and `/resumes/`.
- Contact: email, phone, GitHub, LinkedIn.

## File structure (key)
```
index.html             # Main site
resumes/               # Short-name PDFs (cloud.pdf, devops.pdf, network.pdf, support.pdf)
Resume/                # Descriptive-name PDFs used by live links
.github/workflows/pages.yml  # GitHub Pages deploy workflow
```

## Running locally
```bash
# serve from repo root
python -m http.server 8000
# then open http://localhost:8000/Portfolio/ (or index.html directly)
```

## Deployment
GitHub Actions deploys `main` to GitHub Pages via `.github/workflows/pages.yml`. Push to `main` triggers an automatic publish.

## Updating resumes
Replace the PDFs in both `resumes/` (short names) and `Resume/` (capitalized path used on the page). Keep filenames consistent with links in `index.html`.

## Contact
- Email: manbazhagan18@gmail.com
- Phone: +91 93844 97946
- GitHub: https://github.com/anbazhagan1804
- LinkedIn: https://www.linkedin.com/in/anbazhagan-m-7a2300256