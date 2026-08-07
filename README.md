# Mvndicraft Website

This repository contains the source code for the official web application, designed to be deployed and accessible at [mvndicraft.net](https://mvndicraft.net/). This project serves a community of over 5,000 members.

## 🎨 UI / UX Design (Figma)
The design phase, ergonomics, wireframes, and overall user experience were fully planned and designed beforehand using **Figma** prior to development. The final implementation was executed in **pixel-perfect** accordance with the original design specifications.

![Project Design](https://i.ibb.co/GfL1ZWN5/Capture-d-cran-2026-08-07-120413.png)

## 📱 Responsive & Mobile-First
The application is fully **responsive**, ensuring a seamless and optimized user experience across all devices (mobile, tablet, and desktop). The layout adapts fluidly to various screen sizes, maintaining high usability and performance standards.

## ⚙️ Backend Logic & API Integration
The project leverages Next.js API Routes running on the **Edge Runtime** for ultra-low latency. It integrates an external Minecraft status API (`mcsrvstat.us`) using asynchronous requests (`fetch` with `AbortController` and timeout handling) to dynamically display live server data (such as online player counts) with robust fallback mechanisms.

## 🛠️ Tech Stack & Deployment
* **Framework:** Next.js / React (TypeScript)
* **API / Backend:** Next.js Route Handlers (Edge Runtime)
* **Styling / Design System:** Based on Figma specifications
* **Package Manager:** **pnpm** (for fast, efficient, and disk-space-saving dependency management)
* **Hosting & Deployment:** Deployed globally on **Cloudflare Pages** for high performance and low latency.

## 🚀 Getting Started

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MatthieuClaessens/BlackMist.git
   ```
