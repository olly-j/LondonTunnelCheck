# Tunnel Fee Calculator

The Tunnel Fee Calculator is a modern, responsive web application that calculates toll fees for crossing the Blackwall and Silvertown Tunnels. It features a live countdown timer until charges come into effect (from **7 April 2025**), dynamic fee calculation based on peak and off‑peak periods, multi‑language support (English, Français, Deutsch, Español, 中文), and interactive modals—including an instructions/fee schedule popup and a full‑size map image popup.

## Features

- **Live Countdown Timer:**  
  Displays the remaining time until charges become effective on 7 April 2025. Once the target date is reached, the timer updates with a friendly message.

- **Responsive Design:**  
  The layout adapts gracefully to mobile, tablet, and desktop screens. On wider viewports, the calculator appears alongside a detailed map image.

- **Fee Calculation:**  
  Input the day, time (in HH:MM format), and vehicle type to calculate the applicable toll fee. The logic distinguishes between peak and off‑peak periods.

- **Multi‑Language Support:**  
  A language selector in the header allows users to switch among English, French, German, Spanish, and Chinese. All translatable text (labels, instructions, helper text, error messages, etc.) updates dynamically on the page.

- **Instruction & Fee Schedule Modal:**  
  A small question mark button opens a modal with clear instructions and a complete fee schedule to help users understand the calculation details.

- **Full‑Size Map Popup:**  
  Clicking on the map image opens a modal displaying the full‑size map of Blackwall and Silvertown Tunnels. The image scales responsively to ensure that it is always fully visible.

- **Enhanced Accessibility:**  
  The site uses semantic landmarks, ARIA live regions, keyboard‑accessible interactive elements (including modals and clickable images), and focus trapping in modals to ensure an inclusive experience for all users.

- **Hosted on GitHub Pages:**  
  The application is deployed on GitHub Pages for easy access.

## Demo

You can view the live demo on GitHub Pages:  
[Live Demo](https://olly-j.github.io/LondonTunnelCheck/)

## Getting Started

To run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/olly-j/LondonTunnelCheck.git
