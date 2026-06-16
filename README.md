# Accessible Mesh Video Chat

A lightweight, zero-login, peer-to-peer WebRTC video chat application specifically designed for older adults and individuals with fine motor control challenges (such as Parkinson's Disease).

## Why This Exists
Commercial platforms (Zoom, Jitsi, Teams) introduce heavy friction for seniors through mandatory account creation, complex dashboards, and small user-interface targets. This application removes those barriers entirely, prioritizing extreme ease of use and physical accessibility. I’m a 76-year-old developer living near Bangkok, Thailand, and I built this app to help my own family and friends stay connected across the US and Thailand. It has been tested extensively and is currently deployed and in active use.
I am now looking for an organization, university, or open-source community interested in adopting and maintaining this project long-term.

## Key Features
* **One-Click Joining:** No accounts, passwords, or typing required for the recipient. Clicking a single text link immediately drops the user into the video room.
* **Highlights include:** Screen sharing, file transfer, print screen, print individual user photo, detailed user guide, and a linked youTube video demonstrating features of app.
* **Defensive UX:** The room generator automatically sanitizes inputs (stripping spaces, capital letters, and special characters) behind the scenes to prevent user-end link errors.
* **High-Target Accessibility:** Buttons are oversized, vividly colored, and spaced to accommodate shaky hands or low dexterity.
* **Privacy-First Architecture:** Built using serverless WebRTC mesh architecture. Once the signaling handshake is complete via a lightweight server, video data moves directly between peers.

## Tech Stack
* **Frontend:** Vanilla HTML5, CSS3, JavaScript
* **Protocol:** WebRTC (Peer-to-Peer Mesh)
* **Infrastructure:** Hosted on Fly.dev, leveraging Xirsys for TURN relay fallback.

## License
Distributed under the MIT License. Feel free to host, modify, and scale this to keep communities connected.

## Contact
* **Name:** Donald Little
* **Email:** dlittle644@gmail.com
* **Mobile Number:**: +66 094-555-6198
