# Financial Independence Visualizer

<div align="center">
  <img src="FIVLogoLight.png" alt="FI Visualizer Logo" width="200" />
  <br>
  <em>(Note: Logo adapts to Light/Dark mode settings)</em>
  <br><br>
  <a href="https://samrosati.github.io/FI-Visualizer/">
    <img src="https://img.shields.io/badge/View_Live_Demo-007aff?style=for-the-badge&logo=github&logoColor=white" alt="View Live Demo" />
  </a>
</div>

## 📖 About The Project

**Financial Independence Visualizer** is a financial education tool designed to demonstrate how your current financial habits impact your ability to pursue your passions.

I built this application during my first hackathon, **nwplus.io**, in November 2025.

### The Motivation
Globally, an estimated **79% of people are not engaged or happy with their job**. People in this position often cannot contribute their true ideas to the world because they are forced to work jobs they are not passionate about solely to survive.

We believe that people who obtain the freedom to pursue work that they are passionate about are happier and able to provide more value to others. However, most people do not deeply understand how their current financial habits impact their timeline to freedom.

**This tool bridges that gap.**

## ✨ Features

* **Comprehensive Inputs:** Calculate projections based on Age, Net Worth, Monthly Income, and Monthly Expenses.
* **Adjustable Assumptions:** Fine-tune the projection with specific parameters for Annual Wage Growth, Inflation, ROI (Return on Investment), and Withdrawal Rate.
* **Interactive Visualization:**
    * Visualizes data up to age 100 using **Chart.js**.
    * Toggles to view/hide Net Worth, Income, Expenses, Capital Deposited, and Investment Returns.
* **FI Calculation:** Automatically calculates the specific age you will reach Financial Independence based on your unique "FIRE" number.
* **Progress Tracking:** Displays a dynamic progress bar showing how close you are to your FI target percentage-wise.
* **Dark Mode Support:** Fully responsive light and dark themes that respect user preference.
* **Custom Branding:** Features a custom logo system designed specifically for Light and Dark modes.

## 🛠️ Tech Stack & Design

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla).
* **Libraries:** [Chart.js](https://www.chartjs.org/) for data visualization.
* **Styling:** Custom CSS with CSS variables and flexbox/grid layouts.
* **Design:** Logos and graphic assets were custom-designed using **Affinity Designer**.

## 🚀 How It Works

The application runs a simulation starting from your current age up to age 100. For every year projected, the algorithm:

1.  **Calculates Annual Deposits:** `(Monthly Income - Monthly Expenses) * 12`.
2.  **Calculates Investment Returns:** Applies the user-defined ROI to the current Net Worth.
3.  **Adjusts for Inflation:** Increases both Income (via Wage Growth) and Expenses (via Inflation) for the following year.
4.  **Checks for FI:** Compares the projected Net Worth against the target necessary to sustain expenses at the given Withdrawal Rate.

## 🤝 Acknowledgments

* Built at **nwplus.io Hackathon (Nov 2025)**.
* **Affinity Designer** used for Logo and Vector Graphics creation.
