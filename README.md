# AMET Radar - Traffic Reporting Map 2026

> **AMET Radar is a Progressive Web App that lets communities publish and review traffic incidents on an interactive map with location support across compatible devices.**

[![Platform](https://img.shields.io/badge/Platform-Web%20PWA-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Not%20specified-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/woodevanplh8305/amet-radar-pwa-map?style=flat-square)](https://github.com/woodevanplh8305/amet-radar-pwa-map)

---

<p align="center">
  <a href="https://woodevanplh8305.github.io/amet-radar-pwa-map/">
    <img src="https://img.shields.io/badge/Download-AMET%20Radar%20Latest-brightgreen?style=for-the-badge" alt="Download AMET Radar">
  </a>
</p>

> **[Download AMET Radar](https://woodevanplh8305.github.io/amet-radar-pwa-map/)**

---

[Download Latest Build](https://woodevanplh8305.github.io/amet-radar-pwa-map/)

---

## What AMET Radar Does

AMET Radar brings community-submitted traffic information together on one interactive, location-aware map. Users can inspect incidents by category and limit the results to the portion of the map currently in view, making it easier to concentrate on nearby or relevant events.

The app is delivered as a Progressive Web App and supports shared reports on compatible devices, continuous user-location tracking, and one-to-one report sharing. Community actions can confirm or remove reports, while ownership checks allow contributors to delete their own entries. Rate limiting also helps control excessive submissions.

---

## Core Capabilities

- Publish traffic reports for access from supported devices.
- Follow the user's live location while using the map.
- Classify submissions by traffic incident type.
- Show only reports within the current map viewport.
- Provide community controls for confirming or removing reports.
- Give report creators the ability to delete their own submissions.
- Limit submission frequency to help prevent excessive reporting.
- Share a specific report directly with others.
- Cache the application shell so it can load with offline support.

---

## Getting Started

### Open the hosted application

Visit the published build here:

[Launch AMET Radar](https://woodevanplh8305.github.io/amet-radar-pwa-map/)

Depending on the browser and device, the PWA may be offered for installation through the browser's application or sharing controls.

### Start from source

Download the repository, then enter its directory:

```bash
git clone https://github.com/woodevanplh8305/amet-radar-pwa-map.git
cd REPO
```

Use the repository's configured development server or static hosting process to serve the project. Netlify is also suitable for publishing a hosted deployment.

---

## Using the Map

1. Open AMET Radar in a supported modern browser.
2. Grant location permission if live location tracking is required.
3. Browse the available traffic incidents on the map.
4. Pan or zoom the map to refresh results for the area currently shown.
5. Choose an incident category when creating a new report.
6. Send a report directly when someone else needs its incident and location information.
7. Use the community actions to confirm or remove reports.
8. Remove reports belonging to you once they are no longer useful.

---

## Deployment Configuration

The application relies on its web configuration together with a Supabase-backed service for shared reporting data. Keep deployment-specific values in the project's established configuration or environment mechanism, and avoid placing private service settings directly in browser code.

A deployment may use configuration entries such as:

```text
SUPABASE_URL=<your Supabase project URL>
SUPABASE_ANON_KEY=<your Supabase client key>
```

The exact variable names must match those expected by the project. When deploying with Netlify, its environment settings can supply the values required by the hosted build.

---

## System Requirements

- A current web browser with JavaScript enabled.
- Internet access for shared reports and Supabase-powered functionality.
- Location permission when live user tracking is needed.
- A deployment-capable hosting service, such as Netlify.
- A configured Supabase project for the shared reporting layer.
- Enough browser storage to retain the cached application shell.

---

## Frequently Asked Questions

### Can AMET Radar be installed as a desktop program?

AMET Radar is a Web PWA rather than a traditional desktop application. It runs in a compatible browser and may be installable through browser features supported by the platform.

### Do I have to share my location?

Location permission is required for real-time tracking. Depending on the deployment configuration, users may still browse the map and use other features without enabling location access.

### How does data appear on multiple devices?

The application uses Supabase to store reports, allowing supported clients to retrieve the same shared reporting data.

### Are reports removable?

Yes. Community members can use the available confirmation and removal controls, and owners can delete reports they submitted.

### Where do I provide the service settings?

Set configuration through the project's application configuration or deployment environment. For a Netlify site, inspect the site's environment variable settings and provide the names expected by the project.

### What can cause reports to remain unavailable?

Check the network connection, verify that the Supabase settings have been supplied, and ensure the deployed client is configured with the intended project URL and client key.

### Why does the interface load offline?

The application shell is cached for offline loading. Report data and shared changes depend on network access and may not be available without an active connection.

### How do I receive the newest version?

Open the latest published build using the link above, or update the deployed repository to its current project revision.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
