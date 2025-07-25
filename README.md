# Stress Analysis - Thick Cylinder Stress Calculator 🔩📊

This project is a front-end web application that calculates and visualizes **Hoop Stress** and **Radial Stress** in a thick-walled cylinder under internal and external pressure conditions. The tool is useful for students and engineers studying or working with **Strength of Materials**.

## 🔗 Live Demo
[Click here to try the app]([https://your-live-link-here.com](https://stress-analysis-project.vercel.app/))

---

## 📌 Features

- Takes **user inputs** for:
  - Internal Pressure (Pi)
  - External Pressure (Po)
  - Inner Radius (Ri)
  - Outer Radius (Ro)
- Calculates:
  - Hoop stress (σ_θ)
  - Radial stress (σ_r)
- **Plots** stress distribution curves using HTML5 Canvas or Chart.js
- Clean and responsive user interface built with **HTML, CSS, and JavaScript**

---

## 📷 Preview

![App Screenshot](screenshot.png) <!-- Replace with actual screenshot if available -->

---

## 📚 Background

Based on analytical equations from the **Strength of Materials** domain:
- **Radial Stress**:
  \[
  \sigma_r = \frac{P_i R_i^2 - P_o R_o^2}{R_o^2 - R_i^2} - \frac{(P_i - P_o) R_i^2 R_o^2}{(R_o^2 - R_i^2) r^2}
  \]
- **Hoop Stress**:
  \[
  \sigma_θ = \frac{P_i R_i^2 - P_o R_o^2}{R_o^2 - R_i^2} + \frac{(P_i - P_o) R_i^2 R_o^2}{(R_o^2 - R_i^2) r^2}
  \]
where `r` is the radial distance from the center.

---

## ⚙️ Technologies Used

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**
- **Chart.js** (for plotting)
- **Engineering Mechanics (SoM concepts)**

---


