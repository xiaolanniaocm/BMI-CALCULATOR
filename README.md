# BMI Calculator

A simple Body Mass Index (BMI) calculator prototype built with HTML, CSS, and JavaScript.

## Features

- **Metric units** – Weight in kg, height in cm
- **Imperial units** – Weight in lbs, height in feet and inches
- **BMI categories** – Underweight, Normal, Overweight, Obese
- **Responsive UI** – Clean, modern dark theme

## How to Run

1. Open `index.html` directly in your browser, or
2. Use a local server (e.g., Live Server in VS Code), or
3. Run: `npx serve .` from the project directory

## BMI Formula

```
BMI = weight (kg) / height² (m²)
```

## Category Ranges

| Category    | BMI Range   |
|-------------|-------------|
| Underweight | < 18.5      |
| Normal      | 18.5 - 24.9 |
| Overweight  | 25 - 29.9   |
| Obese       | ≥ 30        |

## Files

- `index.html` – Structure and markup
- `styles.css` – Styling
- `script.js` – Calculation logic
