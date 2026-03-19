# HCI FURNITURE STORE APPLICATION -  FurnishDesignStudio 🛋️

Bridging the gap between imagination and interior design. An HCI-driven, web-based furniture visualization system that empowers designers and customers to plan, customize, and experience spaces in real-time.

[![Vite](https://img.shields.io/badge/Build-Vite-646cff.svg)](https://vitejs.dev/)
[![React](https://img.shields.io/badge/UI-React-61dafb.svg)](https://reactjs.org/)
[![ThreeJS](https://img.shields.io/badge/Graphics-Three.js-black.svg)](https://threejs.org/)
[![HCI Principles](https://img.shields.io/badge/Design-HCI%20Compliant-blueviolet.svg)]()


## 1.  Visuals

<p align="center">
  <img src="./tests/home.png" alt="FurnishDesignStudio Home Preview" width="800">
  <br>
  <b>Figure 1:</b> 



## 2. About / Description
**FurnishDesignStudio** is a specialized visualization tool designed for furniture retail environments. By integrating **Human-Computer Interaction (HCI)** principles, the application ensures high usability and efficiency for two primary user tiers:
* **Primary Users:** Professional Interior Designers requiring precision and portfolio management.
* **Secondary Stakeholders:** In-store customers who need a clear visual understanding of furniture placement.

The system allows users to define room specifications, interactively place items via drag-and-drop, and instantly visualize the result in a WebGL-powered 3D environment.

## 3. Tech Stack & Architecture
The project is built as a **Single Page Application (SPA)** with a modular, component-based architecture:

* **Core Engine:** React + Vite (Fast development & optimized builds).
* **3-D Graphics:** React Three Fiber (R3F) & Drei (Real-time WebGL rendering).
* **Routing:** React Router for seamless navigation (Login, Dashboard, Catalog, Workspace).
* **State & Persistence:** React Hooks (`useState`, `useEffect`) and LocalStorage API.
* **HCI Logic:** Implemented "Direct Manipulation" patterns for scaling, rotating, and placing objects.

## 4. Project Structure
Each directory represents a specific phase of the project lifecycle. Click the links below for detailed documentation:

* **[/docs](./docs)**: **Analysis & Research** — Detailed functional/non-functional requirements, HCI user personas, and technical specifications.
* **[/design](./design)**: **UI/UX & Assets** — Low-fidelity wireframes, high-fidelity Figma/Adobe XD export.
* **[/app](./app)**: **Development Source** — Core React/Vite application including Login, Dashboard, Catalog, and 2D/3D Workspace components.

## 5. Functional Requirements
* **Portfolio Management:** Secure designer login with Client Name search and full CRUD project capabilities.
* **Room Setup:** Hybrid input via manual entry or Shape Templates (L-shape/Square).
* **2D Layout Engine:** Top-down drag-and-drop grid with Auto-Scaling and interactive rotation handles.
* **3D Graphics:** One-click conversion to 3D space featuring Orbit, Pan, and Zoom walkthroughs.
* **Customization:** Selective color editing and Global Room Themes for rapid aesthetic changes.
* **Handover:** Generation of unique Viewer Links and PDF exports with precise layout dimensions.

## 6. Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation & Setup
1. **Clone the repository**
2. ```
   cd app
   ```
3. ```
   cd FurnishDesign
   ```
4. ```
   npm install
   npm run dev
   ```

## 7. License

