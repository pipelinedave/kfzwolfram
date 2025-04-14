# KFZ Wolfram Project Requirements Document (PRD)

## Overview
KFZ Wolfram is a used-car dealership in Bad Honnef, Germany, operating under "Gebrauchtwagenhandel." The goal of this project is to create a static, responsive, and SEO-optimized landing page to serve as a digital business card for the dealership. The page will feature the business identity, contact information, and car portfolios from **mobile.de** and **autoscout24.de** with embedded listings.

The page must be easy to maintain and should integrate cleanly into GitHub Pages.

## Core Requirements

### 1. **Business Identity**
- **Name**: KFZ Wolfram
- **Location**: Rottbitzer Str. 32, 53604 Bad Honnef, Germany
- **Phone Number**: 01520 5907647
- **Email**: [Insert email address]

### 2. **Car Listings**
- Embed or display car listings directly from **mobile.de** and **autoscout24.de**. This can be done via widgets, embeddable feeds, or by using API-based approaches, ensuring the car listings are up-to-date.
- If embedding widgets is not possible, show an excerpt of the current listings.

### 3. **Design & Aesthetics**
- The design should be minimalist, resembling a digital business card with clear typography and professional layout.
- No dark mode toggle; the site will always have a light, consistent design.
- Use **Material You** design principles for a modern and responsive layout.
- A **header section** with the dealership's name, location, and contact information should be visible at all times.
- A **contact section** with the dealership’s phone number and email should be included for easy accessibility.
- A **footer** with links to **mobile.de** and **autoscout24.de** car portfolios.
- **Google Maps integration** for visualizing the dealership’s location.

### 4. **SEO & Accessibility**
- Full on-page SEO setup using appropriate **meta tags**, **headings**, and **descriptive titles** in German.
- **Schema.org** structured data for search engine optimization.
- Accessibility should be a priority: Ensure keyboard navigability and screen reader compatibility.
- Use clear, descriptive alt text for all images.

### 5. **Hosting & Deployment**
- **GitHub Pages** for hosting to avoid hosting fees, making use of its CI/CD features.
- The project should be initialized in GitHub with a version-controlled workflow.

### 6. **Additional Features**
- Use **contact info** directly (email, phone, address) without embedding a contact form.
- The landing page should be mobile-friendly and fully responsive.
- The page should load quickly, and minimal dependencies should be used.

## Technical Requirements

### 1. **Tech Stack**
- **HTML5**: For the markup and structure of the page.
- **CSS3**: For styling, following Material You design principles.
- **JavaScript (if necessary)**: For dynamic elements, like embedded car listings.
- **GitHub Pages**: For deployment.
- **Google Maps API**: For dealership location integration.

### 2. **CI/CD**
- Use **GitHub Actions** to automate deployments to GitHub Pages when updates are made to the repository.

## Deliverables
- A fully functioning static landing page that meets all the requirements listed above.
- A repository in GitHub with clear commit messages and a structured file organization.
- An automatic deployment pipeline through GitHub Actions.

## Timeline
- **Week 1**: Complete the landing page design, layout, and functionality.
- **Week 2**: Complete the SEO and accessibility optimizations.
- **Week 3**: Test the car listing integration and deploy the site to GitHub Pages.
