# AKCAF Youth Club — Al Rafisah Hiking Trail

A responsive single-page event website for the **AKCAF Youth Club** hiking event at **Al Rafisah Hiking Trail** on **18 October 2026**.

## Overview

The website is designed as an event landing page with a warm cream, black, and gold visual style. It presents the event information, registration area, and a personal packing checklist for participants.

## Event Information

- **Organizer:** AKCAF Youth Club
- **Event:** Hiking / trekking experience
- **Date:** 18 October 2026
- **Destination:** Al Rafisah Hiking Trail
- **Eligible participants:** Youth aged 15–35

## Main Sections

### 1. Intro / Opening Animation
The page starts with an AKCAF Youth Club intro screen containing:
- Embedded AKCAF logo
- Introductory text
- Animated line
- Fade transition into the main website

The intro automatically transitions to the main page after the opening animation.

### 2. Hero Section
The hero area introduces the event with the main visual presentation and AKCAF Youth Club branding.

### 3. Event Details
The event details section includes:
- Date
- Destination
- Who Can Join
- The Experience
- Respect the Trail
- Registration information

### 4. What to Bring — Per Person
The website includes a dedicated packing section titled **“Pack for the trail.”**

Participants are asked to bring:

- 🥾 Hiking shoes or sturdy boots
- 👕 Two layers of comfortable clothing
- 🕶️ Sunglasses
- 🧢 Hat or cap
- 🎒 Backpack

A black horizontal divider is displayed between the Event Details and What to Bring sections on mobile screens to provide clearer visual separation.

### 5. Registration
The page includes a registration area with an embedded Google Form so visitors can register directly from the website.

There is also an option to open the registration form separately.

### 6. Footer
The footer identifies the site as:

> AKCAF Youth Club · AKCAF Events · 2026

## Technical Details

This project is intentionally contained in a single HTML file:

```text
index.html
```

The file contains:

- HTML structure
- CSS styling
- JavaScript interactions
- Embedded image data

No separate local CSS or JavaScript files are required for the current version.

## Responsive Design

The website is designed to work on both desktop and mobile screens.

The CSS includes a mobile breakpoint for smaller screens. Mobile-specific styling is used to improve spacing, readability, and section separation.

## Animations & Interaction

The page currently includes:

- Intro logo animation
- Intro fade-out transition
- Animated intro line
- Smooth scrolling
- Subtle hero pointer/parallax movement
- Reduced-motion support through `prefers-reduced-motion`

## Running the Website

### Option 1 — Open Locally

Simply open:

```text
index.html
```

in a modern web browser.

### Option 2 — Host Online

Upload `index.html` to a web hosting service or static hosting platform.

Because the main visual assets are embedded directly in the HTML, the page does not require a separate image folder for those embedded assets.

## Editing the Website

Most visual styling can be changed inside the `<style>` section near the top of `index.html`.

The main color variables are defined in `:root`, including:

```css
--gold
--gold2
--ink
--cream
--white
```

Event text can be edited directly inside the corresponding HTML sections.

## Important Notes

- Keep the Google Form URL unchanged unless the registration form itself is replaced.
- If the event date, location, eligibility, or packing requirements change, update the corresponding text in `index.html`.
- Test the page on a mobile device after making responsive-design changes.
- Keep a backup copy before making major edits.

## Current Version

**Website:** AKCAF Youth Club Event Website  
**Event:** Al Rafisah Hiking Trail  
**Date:** 18 October 2026  
**File:** `index.html`
