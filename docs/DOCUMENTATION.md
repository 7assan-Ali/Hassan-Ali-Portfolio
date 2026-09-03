# Hassan Ali Portfolio — Documentation

## 1. Overview

This repository contains the personal portfolio website of **Hassan Ali — Data Analyst | AI & Data Science**.

The portfolio is designed to present Hassan's technical skills, academic background, training, certifications, projects, and contact information through a modern, responsive web experience.

> **Value Proposition:** I help businesses turn raw data into actionable insights and smarter decisions through Python, SQL, Excel, Power BI, and AI.

---

## 2. Objectives

The portfolio is built to:

- Present Hassan Ali's professional profile clearly.
- Showcase practical data analysis and business intelligence projects.
- Demonstrate proficiency with Python, SQL, Excel, Power BI, Tableau, and related tools.
- Highlight Machine Learning and Generative AI knowledge.
- Provide a professional presentation of certifications and training.
- Make it easy for recruiters, clients, and collaborators to review the work.
- Provide a lightweight website that can be hosted directly with GitHub Pages.

---

## 3. Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic content |
| CSS3 | Layout, responsive design, animations, themes and visual styling |
| JavaScript | Interactions, filtering, modals, theme switching and UI behavior |
| Font Awesome | Interface icons |
| Google Fonts | Typography |
| GitHub | Version control and source repository |
| GitHub Pages | Static website hosting |

The project is intentionally **frontend-only**. No backend server, database, authentication system, or API server is required.

---

## 4. Project Structure

```text
Hassan-Ali-Portfolio/
│
├── .github/
│   └── workflows/              # Repository automation when required
│
├── assets/
│   └── hassan-ali-logo.svg     # Portfolio branding/logo
│
├── docs/
│   └── DOCUMENTATION.md        # Technical project documentation
│
├── index.html                  # Main portfolio website
├── cv.html                     # Online CV page
│
├── profile.jpeg                # Profile image
│
├── olist.jpg                   # Olist project visual
├── fi_used-car-Price-trends.jpg# Used car project visual
├── Dashboard1.jpeg             # Dashboard visual
├── Dashboard2.jpeg             # Dashboard visual
├── PESTLE-Analysis-of-BMW.jpg  # BMW analysis visual
│
├── README.md                   # Repository overview
└── certificate/project images  # Training and certification visuals
```

---

## 5. Main Website

The main entry point is `index.html`.

It contains the portfolio's primary sections:

1. Hero / Introduction
2. About
3. Education
4. Technical Skills
5. Projects
6. Experience & Training
7. Certifications
8. Soft Skills
9. Contact

### Hero Section

The hero section introduces Hassan as a Data Analyst and AI & Data Science student. It includes the profile image, animated role text, primary calls to action, and the supporting message:

**Data → Insights → Impact**

The phrase is displayed around the profile image rather than over the image itself.

### About & Education

The portfolio identifies Hassan as a Fourth-Year student at **Beni Suef National University, Faculty of Computers and Artificial Intelligence**, studying Computer Science & Artificial Intelligence with expected graduation in 2027.

### Technical Skills

The portfolio highlights:

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- SQL
- SQL Server
- Power BI
- DAX
- Power Query
- Excel
- Tableau
- Machine Learning
- Generative AI
- Git & GitHub

### Soft Skills

The portfolio includes:

- Communication
- Teamwork
- Problem Solving
- Time Management
- Presentation
- Adaptability

---

## 6. Projects

The portfolio currently presents the following verified projects/work:

### Olist E-Commerce Data Analysis

End-to-end e-commerce analysis using the Brazilian Olist dataset, covering data preparation, exploratory analysis, customer behavior, sales performance, and business insights.

### Power BI Car Sales Dashboard

A Power BI dashboard project focused on sales analysis and business intelligence visualization.

### Outlier Detection & Treatment

A data-quality project focused on identifying and treating outliers using statistical approaches such as IQR and Z-Score.

### SQL Data Cleaning

A SQL-focused project demonstrating data cleaning and preparation techniques.

### Excel Data Analysis

A practical Excel analytics project demonstrating spreadsheet-based analysis and reporting.

### Tableau Sales Analysis

A Tableau project focused on sales analysis and visualization.

### Python Data Analysis Projects

A collection of Python-based data analysis work using common data-analysis libraries.

### E-Commerce System

An e-commerce system project included as part of the portfolio work showcase.

---

## 7. Training & Credentials

The portfolio presents the following training and credentials:

- **Digital Egypt Pioneers Initiative (DEPI)** — Data Scientist Track — **In Progress**
- **National Telecommunication Institute (NTI)** — Data Analysis Training — **Final Score: 98%**
- **IBM AI Developer Professional Certificate**
- **DeepLearning.AI Data Analytics Professional Certificate — Coursera**
- **freeCodeCamp Generative AI Bootcamp**

---

## 8. CV

The repository includes a dedicated `cv.html` page containing the online version of Hassan Ali's CV.

The CV includes:

- Professional summary
- Education
- Technical skills
- Projects
- Certifications and training
- Soft skills
- Contact information
- GitHub profile

---

## 9. Design System

The website uses a premium dark-first visual system with an optional light theme.

### Visual characteristics

- Dark navy background
- Cyan/blue accent gradients
- Glassmorphism-inspired cards
- Rounded UI components
- Animated profile presentation
- Subtle background grid
- Hover interactions
- Scroll/reveal animations
- Responsive layouts
- Accessible contrast-oriented typography

### Typography

The interface uses **Inter** for general text and **Space Grotesk** for headings and branding.

---

## 10. Responsive Design

The portfolio is designed for:

- Desktop
- Laptop
- Tablet
- Mobile

Responsive CSS adjusts navigation, project grids, skill cards, hero layout, typography, and spacing according to viewport size.

---

## 11. Interactions

The website provides client-side interactions including:

- Dark/light theme switching
- Mobile navigation
- Active navigation state
- Scroll progress indicator
- Project search/filtering
- Project detail modal
- Certification image lightbox
- Expandable experience/training cards
- Copy Email functionality
- Interactive hover states
- Animated hero/profile elements

All of these features run in the browser without a backend.

---

## 12. Deployment

The website is intended to run through **GitHub Pages** from the repository's `main` branch.

Expected public website:

```text
https://7assan-ali.github.io/Hassan-Ali-Portfolio/
```

Online CV:

```text
https://7assan-ali.github.io/Hassan-Ali-Portfolio/cv.html
```

### Deployment model

```text
GitHub Repository
       │
       ▼
   main branch
       │
       ▼
  GitHub Pages
       │
       ▼
 Static HTML/CSS/JS Website
```

No build server or package installation is required for the static website.

---

## 13. Local Development

Because the portfolio is a static frontend project, it can be opened directly in a browser.

For a better development experience, a local static server can be used.

Example using Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## 14. Updating the Portfolio

### Add a project

1. Add the project's image to the repository.
2. Add the project card to `index.html`.
3. Add the repository link if available.
4. Add a concise project description.
5. Test the project card on desktop and mobile.

### Add a certificate

1. Add the certificate image to the repository.
2. Add the certificate entry to the certification section in `index.html`.
3. Use a clear title and provider name.
4. Test the lightbox behavior.

### Update the CV

Edit `cv.html` and keep its content consistent with the portfolio. Avoid adding unverified experience, metrics, credentials, or claims.

---

## 15. Quality & Content Principles

The portfolio follows these principles:

- **Accuracy:** only verified projects, skills, training, and credentials are presented.
- **Clarity:** content is concise and recruiter-friendly.
- **Professionalism:** visual design and copy are intended for professional use.
- **Responsiveness:** the interface should remain usable across screen sizes.
- **Performance:** unnecessary backend infrastructure is avoided.
- **Maintainability:** the project uses a simple static architecture.
- **Consistency:** portfolio and CV information should remain synchronized.

---

## 16. Contact

**Hassan Ali**  
Data Analyst | AI & Data Science

Email: `hassanali.elnagy@gmail.com`

GitHub: `7assan-Ali`

---

## 17. Repository

The source code is maintained in the GitHub repository:

`7assan-Ali/Hassan-Ali-Portfolio`

This documentation describes the current architecture, content, deployment model, and maintenance approach of the portfolio.
