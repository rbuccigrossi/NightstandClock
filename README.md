# Nightstand Clock & Calendar

A simple, clean, web-based nightstand clock and calendar application designed primarily for iPhones and tablets.

## The Problem

Many users enjoy using their iPhone or tablet as a nightstand clock. However, built-in features like iPhone's nightstand mode often turn off the display after a short period to save power or prevent screen burn-in. This application aims to provide a persistent nightstand clock experience.

## Features

*   **Analog Clock Display:** A clear and easy-to-read analog clock face that updates every second.
*   **Monthly Calendar:** Displays the current month with the current day highlighted.
*   **Automatic Calendar Updates:** The calendar automatically refreshes to the new day at midnight.
*   **Screen Wake Lock:** Prevents your device's screen from automatically turning off. This ensures the clock remains visible all night.
    *   **How to use:** When you first load the page, if your browser supports Screen Wake Lock, a "💤" icon will appear in the top-right corner. Simply tap or click anywhere on the screen to activate the wake lock and hide the icon. The screen will then stay on. If the lock is released (e.g., if you switch tabs and come back, or the system overrides it), the "💤" icon will reappear, and you can tap the screen again to re-activate it.
*   **Responsive Design:** Adapts to both portrait and landscape orientations.

## Usage

Simply open the `index.html` file in a web browser on your device.

## Browser Compatibility

The core clock and calendar functionalities work in most modern web browsers.

The **Screen Wake Lock API** is crucial for keeping the screen on. This feature is supported by:
*   Chrome (Desktop & Android)
*   Edge (Desktop)
*   Opera (Desktop & Android)

*Compatibility may vary on iOS (Safari) due to Apple's implementation of the Screen Wake Lock API. It's generally more restrictive.*

## Files

*   `index.html`: Contains all the HTML, CSS, and JavaScript for the application.
*   `clock.png`: Icon for the application (used for PWA features like "Add to Home Screen").
*   `manifest.json`: Web app manifest for PWA capabilities.
*   `README.md`: This file.
