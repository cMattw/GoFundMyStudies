# GoFundMyStudies

A crowdfunding platform designed specifically for students and educational organizations to fund their academic expenses and initiatives.

## Overview

GoFundMyStudies connects students seeking financial support with a community of supporters. Users can register, create fundraiser campaigns, receive donations, and track their progress through a personal dashboard.

## Project Structure

```
GoFundMyStudies/
├── index.html          # Landing page
├── browse.html         # Browse all active campaigns
├── signup.html         # Sign in / Sign up
├── create-post.html    # Create a new fundraiser campaign
├── post-details.html   # Individual campaign page with donation widget
├── dashboard.html      # User dashboard (campaigns, notifications, profile, security)
└── style.css           # Global stylesheet
```

## Pages

- **Landing Page** — Overview of the platform, how it works, FAQs, and footer
- **Browse Campaigns** — Grid view of all published campaigns with author profiles
- **Sign In / Sign Up** — Account creation and authentication
- **Create Post** — Rich-text campaign editor with image upload
- **Campaign Details** — Full campaign view with live donation functionality
- **Dashboard** — Personal hub with tabs for campaigns, notifications, profile settings, and password management

## Features

- User registration and login with localStorage-based session management
- Rich-text campaign editor powered by Quill.js
- Campaign cover image upload with base64 preview
- Live donation tracking with real-time total updates
- Notification feed for incoming donations
- Profile management including avatar upload and organization info
- Author profile display on browse cards and campaign detail pages

## Tech Stack

- **HTML5** — Structure
- **CSS3** — Styling and responsive design
- **Vanilla JavaScript** — Interactivity and localStorage data management

## Data Storage

All data is stored client-side using the browser's `localStorage`. No backend or database is required.

| Key                  | Contents                          |
|----------------------|-----------------------------------|
| `users`              | Array of registered user accounts |
| `currentUser`        | Currently logged-in user session  |
| `studyPosts`         | Array of published campaigns      |
| `studyNotifications` | Array of donation notifications   |

## Deployment

This project is deployed using GitHub Pages. Visit the live site at: https://cmattw.github.io/GoFundMyStudies/

## Authors

- John Matthew Agoncillo
- Clark Eugene Dimarucut
- Hale Styx Igmasin
- Jasper Capili
- John Paul Ceballos

## Course

ITEC-50B Web Systems and Technology - 1st Year, 2nd Semester

## Last Updated

May 2026