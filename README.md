# Association of Apartment Owners (J21 & J22) — Official Website

> **"A stronger home starts with us."**  
> Bringing the residents of J21 and J22 together through transparent governance, thoughtful stewardship, and a shared commitment to community.

---

## 🏛️ Project Overview

This repository hosts the official static website for the **Association of Apartment Owners (J21 & J22)**, designed specifically for seamless hosting on **GitHub Pages**.

### 🌟 Key Features
- **Hero & Branding**: Community values, mission statement, quick navigation pills, and dual-tower statistics.
- **Section (01) Notice Board**: Urgent maintenance notices, quarterly billing updates, and RFID vehicle pass circulars.
- **Community Calendar / Upcoming Events**: Structured event cards with date blocks (`DAY`/`MONTH`), times, locations, and interactive RSVP / Add to Calendar buttons.
- **Section (02) Leadership**: 6 executive board members with designated roles (President, Vice President, Secretary, Joint Secretary, Treasurer, Joint Treasurer) and unit representations.
- **Section (03) Representation**: 16-member board table across Towers J21 & J22 in an editorial alabaster format.
- **Section (04) Governance**: Foundational meeting resolutions adopted to formally empower the Association with verified checkmarks.
- **Section (05) Contact the Board**:
  - **Official Address**: J21/22, SP Shukhobrishti Complex, Action Area III, Newtown, Rajarhat, Kolkata — 700135 (with Google Maps link).
  - **Phone**: +91 97341 01442 (one-tap dialer).
  - **Email**: owners_associationj2122@gmail.com (one-tap mailto).
  - **Gate & Helplines**: Tower J21 Gate 1 (Intercom 2100), Tower J22 Gate 2 (Intercom 2200), and 24/7 Control Room.
  - **FormSubmit Integration**: Secure, AJAX-powered resident inquiry form delivering directly to the board inbox without page reloads.

---

## 🚀 GitHub Pages Deployment

The website is housed in the `docs/` folder, which GitHub Pages natively supports.

### How to Enable GitHub Pages:
1. Navigate to your repository on GitHub (`https://github.com/aniruddhamukherjee/j21-22-web`).
2. Go to **Settings** &rarr; **Pages** (in the left sidebar).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` (or your default branch) and choose the `/docs` folder from the dropdown.
4. Click **Save**.
5. Within 1–2 minutes, your website will be live at:
   `https://aniruddhamukherjee.github.io/j21-22-web/`

---

## 📬 Contact Form Configuration (FormSubmit)

The inquiry form uses **FormSubmit** with an obfuscated token alias to keep email addresses safe from scraping bots:
- **Active Token**: `69852239d3bcb6cfb29189751f826e88`
- **Submission Mode**: Background AJAX `fetch` with on-page status feedback and toast alert.

### Switching the Recipient Email in the Future:
To change the recipient email in `docs/index.html`:
1. Open `docs/index.html`.
2. Locate `https://formsubmit.co/69852239d3bcb6cfb29189751f826e88` and `https://formsubmit.co/ajax/69852239d3bcb6cfb29189751f826e88`.
3. Replace the token with your new email address or a new FormSubmit token.

---

## 💻 Tech Stack
- **Structure**: Semantic HTML5 (W3C compliant, accessibility tags, OpenGraph SEO tags).
- **Styling**: Vanilla CSS (CSS Custom Properties, responsive clamp typography, midnight navy & warm alabaster themes, micro-animations).
- **Typography**: Google Fonts — *DM Serif Display* & *Plus Jakarta Sans*.
- **Icons**: Inline scalable SVGs (zero external font/icon library dependencies).
- **Logic**: Vanilla JavaScript for smooth anchor transitions, dynamic notifications, and asynchronous form dispatch.