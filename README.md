# BlooHealth × HealthBook+ — Online Meeting Booking Page

This repository contains a lightweight, static landing page hosted on **GitHub Pages**, designed to allow clients to easily book meetings with a BlooHealth Advisor or a HealthBook+ Team Member through **Calendly**.

The website is available in English and Greek, with a language switcher connecting the two versions.

---

## Features

- Clean, minimal UI with subtle animations
- Responsive layout for mobile, tablet, and desktop
- Two meeting types displayed as separate branded cards
- English and Greek language versions
- Direct Calendly integration with no backend required
- BlooHealth × HealthBook+ branding and colors
- Link to the BlooHealth website
- Hosted entirely on GitHub Pages

---

## Project Structure

```text
/
├── index.html                         # English booking page
├── style.css                         # Shared website styles
├── README.md
├── assets/
│   └── bloohealth-healthbook.png      # Combined BlooHealth × HealthBook+ logo
└── el/
    └── index.html                     # Greek booking page
```

Both language versions share the same stylesheet and logo asset.

---

## Meeting Types

The booking page offers two meeting options:

1. **Meeting with a BlooHealth Advisor**
2. **Meeting with a HealthBook+ Team Member**

Each meeting card redirects the visitor to its corresponding Calendly booking page. Separate Calendly links are used for the English and Greek versions.

---

## Customization

To adapt this page to your needs:

1. **Update meeting links**
   - Replace the Calendly URLs in `index.html` and `el/index.html` with the relevant event links.

2. **Change the website link**
   - Update the `BLOOHEALTH SITE` link in both language pages.

3. **Change branding**
   - Replace `assets/bloohealth-healthbook.png` with the updated logo asset.
   - Update the color variables and card gradients in `style.css`.

4. **Update page content**
   - Edit the meeting titles, descriptions, durations, or footer text directly in each language's `index.html` file.

---

## Deployment

This site is designed to be deployed using **GitHub Pages**.

To publish:

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Select the `main` branch and root directory.
4. Access the site through the generated GitHub Pages URL.

The root `index.html` serves the English page. The Greek version is available under `/el/` and can be reached through the language switcher.

---

## Booking Flow

1. The client opens the booking page.
2. The client selects either the BlooHealth or HealthBook+ meeting option.
3. The client is redirected to the corresponding Calendly page.
4. A date and time are selected.
5. The booking is confirmed through Calendly.

---

## Current Links

- **BlooHealth website:** `https://bloohealth.framer.website/`
- **BlooHealth meeting — English:** `https://calendly.com/novaxia/meetingwithbloohealth`
- **BlooHealth meeting — Greek:** `https://calendly.com/novaxia/meetingwithbloohealthgr`
- **HealthBook+ meeting — English:** `https://calendly.com/novaxia/meetingwithhealthbook`
- **HealthBook+ meeting — Greek:** `https://calendly.com/novaxia/meetingwithhealthbookgr`

---

## License

The source code may be used and maintained for this booking website. Branding assets, including the BlooHealth, HealthBook+, Novaxia Group names, logos, and written content, are not licensed for reuse without permission.

---

The structure remains ready for future enhancements such as inline Calendly embeds, analytics, additional languages, or a custom domain.
