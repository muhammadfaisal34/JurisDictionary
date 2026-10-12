# JurisDictionary® App Prototype

Interactive mobile web prototype of the **JurisDictionary® Official Tactics Course** ("How to Win in Court").

## Features

- **Interactive Mobile Shell**: Device simulator with live screen switcher, search filter, and dark/light mode toggle.
- **26 Complete Screens**:
  - **Getting Started & Onboarding**: Splash, Onboarding steps 1–3, Sign In, Two-Factor Verification.
  - **Main Experience**: Home Screen (and Alt), Course Preview, Course Includes, Course Content, Tutoring, Main Menu, Profile Screen.
  - **Evidence Rules Series**: Parts 1, 2, 3, The Key to Winning, Winning Made Easy.
  - **Order & Checkout**: Order Screen, Order (Alt - Gift a Friend), Renew Screen ($89 Renewal Offer).
  - **About & Resources**: Student Reviews, About Us, Reference & Rules, How to Control Judge, Extras & Bonuses, Official Rules of Court.
- **Modern UI Stack**:
  - Tailwind CSS v4
  - Iconify Icons
  - Custom JurisDictionary typography (Playfair Display, Plus Jakarta Sans, Inter, JetBrains Mono)
  - Seamless in-app navigation and responsive bottom bar.

## Running Locally

To run the prototype viewer locally:

```bash
# Using npx serve (recommended)
npx serve .

# Or using any static HTTP server (e.g., Python)
python -m http.server 3000
```

Open `http://localhost:3000` in your web browser.

## Security & Secrets

Sensitive credentials and API keys (such as `SLEEK_API_KEY`) must never be committed or published. All `.env` files are strictly excluded via `.gitignore`. A `.env.example` file is provided as a template.
