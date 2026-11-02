# SakhiShield

**Safe access. Trusted support. Greater empowerment.**

A privacy-first women safety and empowerment web prototype built for **UN SDG 5 (Gender Equality)**, also aligned with SDG 10 and SDG 16.
Team EmpowerHer | Milestone 2

> **Prototype notice:** This is a student project. All data is sample data, nothing is saved after a page refresh, and no real SOS message, SMS or call is sent. It cannot replace police or emergency services.

## Problem

Women and girls can face harassment or unsafe situations and may struggle to reach help quickly. Many safety apps track location continuously, and accidental SOS presses cause confusion. Low battery, poor connectivity and language barriers make things worse.

## Features

- **Emergency SOS button** with a **10-second cancel timer** to prevent accidental alerts (Cancel / Send Now)
- **Consent-based location sharing**: only during SOS, for 15 minutes, or off
- **Trusted Contacts** list with an add-contact form
- **Quick-access helplines**: 112 (National Emergency), 1091 (Women Helpline), 181 (Women Support Helpline)
- **Language toggle**: English / Hindi (main headings)
- **Low-Data Mode** that switches the alert to an offline SMS fallback label
- **Activity log** showing the latest action

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Google Fonts (Inter)
- Vanilla JavaScript (no framework, no backend)

## How to Run

1. Clone the repository:
   ```
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `index.html` in any web browser. No installation or server is needed.
3. An internet connection is needed once to load the Tailwind CDN and Google Font.

**Live demo (GitHub Pages):** `https://<your-username>.github.io/<repo-name>/`

## How to Use

1. Press **SOS**, then **Cancel Alert (I am Safe)** within 10 seconds to cancel, or **Send Now** to send immediately.
2. Choose a location-sharing option under **Consent-Based Location Sharing**.
3. Add a name and phone number under **Trusted Contacts**.
4. Click a helpline button to simulate a call.
5. Use the **Language** dropdown and **Low-Data Mode** button in the header.

## Project Structure

```
.
├── index.html
├── README.md
├── docs/
│   ├── SakhiShield-Synopsis.pdf
│   ├── SakhiShield-Design.pdf
│   └── SakhiShield-Test-Results.pdf
└── screenshots/
```

## Documentation

- [Synopsis](docs/SakhiShield-Synopsis.pdf)
- [Design Description](docs/SakhiShield-Design.pdf)
- [Test Run Results](docs/SakhiShield-Test-Results.pdf)

## Limitations and Next Steps

- No data is saved after refresh, and there is no login
- No real SMS gateway or live GPS
- Language toggle translates only the main headings

Planned: a real database,
