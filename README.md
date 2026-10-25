# CPD Playground

A cross-platform Expo and React Native sandbox for learning app structure and interface patterns. The current app is based on Expo Router’s starter flow, with Home and Explore routes and reusable themed components.

## What’s in the app

- **Home screen:** a welcome view with development tips that adapt to web, simulator, and physical-device contexts.
- **Explore screen:** a second route for experimenting with the app’s navigation and content.
- **Shared UI:** themed text and view components, hint rows, animated icons, and platform-aware tab icons.
- **Multi-platform setup:** Expo configuration for Android, iOS, and web, with TypeScript source.

## Project map

- `src/app/` — Expo Router screens and shared navigation layout.
- `src/components/` — reusable and platform-specific interface components.
- `src/constants/theme.ts` — shared colors, spacing, and layout values.
- `src/hooks/` — theme and color-scheme helpers.
- `app.json` — Expo app configuration.
- `package.json` — scripts and dependencies.
- `scripts/reset-project.js` — optional script for resetting the starter project.

## Start developing

Install dependencies and start Expo:

```bash
npm install
npx expo start
```

From the Expo CLI, choose a web browser, Android emulator, iOS simulator, or a connected development device. The current screens remain a starter/learning playground rather than a finished product.

## Technology

Expo, Expo Router, React Native, TypeScript, and React Native Web.