# Roof Area Calculator

## Overview
The **Roof Area Calculator** is a simple web application that calculates the total roof surface area based on user inputs, including roof width, length, and pitch. It also factors in a customizable waste percentage to account for material overage.

## Features
- Input fields for **roof width**, **roof length**, **roof pitch (x/12)**, and **waste percentage**.
- A **Calculate** button to determine the total roof surface area.
- Instant display of results with the adjusted total including waste.
- Lightweight and responsive design for easy use on mobile and desktop.

## How It Works
1. Enter the roof width and length in feet.
2. Enter the roof pitch (rise per 12 inches of run).
3. Adjust the waste percentage (default is 15%).
4. Click the **Calculate** button to get the total roof area.

The calculation follows the formula:
```
Slope Factor = sqrt(pitch^2 + 12^2) / 12
Rafter Length = (Width / 2) * Slope Factor
Total Roof Area = 2 * (Rafter Length * Length)
Total with Waste = Total Roof Area * (1 + Waste Percentage)
```

## Hosting Instructions
To use this web app, you can host it on:
- **GitHub Pages** (Upload the HTML file and enable GitHub Pages in settings)

## Adding to iPhone Home Screen
1. Open the hosted link in **Safari**.
2. Tap the **Share** button.
3. Select **"Add to Home Screen"**.
4. Name it and tap **Add**.

## Future Improvements
- Allow users to choose different roof types (hip, shed, etc.).
- Add a material estimator for shingles, underlayment, etc.
- Save past calculations for reference.

---
Built for quick and efficient roofing calculations! 🚀

