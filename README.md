# HODL IPTV M3U Link Checker

![HODL IPTV M3U Link Checker](https://m3uchecker.netlify.app/img/logo.png)

A lightweight, responsive web application to check the availability of IPTV links from M3U playlists or URLs. Built with HTML, CSS, and JavaScript, this tool allows users to upload M3U files or input URLs, verify link status, play streams, export results, and manage local history.

Hosted live at: [https://m3uchecker.netlify.app/](https://m3uchecker.netlify.app/)

## Features

- **Link Checking**: Quickly verify the availability of IPTV links with optimized batch processing (50 links at a time).
- **Responsive Design**: Fits seamlessly on desktop and mobile devices with a scrollable, well-fitted results table.
- **Local History**: Persists uploaded files/URLs and results in `localStorage` until explicitly cleared.
- **Export Options**: Export available links as M3U or JSON files.
- **Stream Playback**: Play streams directly in the browser using HLS.js, with an option to open in external players.
- **Dark Mode**: Toggle between light and dark themes, with automatic detection of system preferences.
- **Filters**: Filter results by status (All, Available, Unavailable) and type (All, JSON, M3U).
- **Progress Tracking**: Visual progress bar with smooth animations during link checks.

## Installation

To run this app locally or contribute to its development, follow these steps:

### Prerequisites
- A modern web browser (e.g., Chrome, Firefox, Edge).
- No server-side dependencies—just pure client-side code!

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/bugsfreeweb/M3ULinkChecker.git
   cd M3ULinkChecker
