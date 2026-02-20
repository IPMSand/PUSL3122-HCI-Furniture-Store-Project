## 1. Functional Requirements 
*Core features required for a professional design workflow.*
- [View Detailed Functional Specifications](./details/detailed-fr.md)

| Function | Category | Key Requirements | Rationale |
| :- | :--- | :--- | :--- |
| 01 | **1. Data & Portfolio** | Secure Login, Search by Client, CRUD (Save/Edit/Delete). | Professional project management & fast retrieval. | 
| 02 | **2. Environment** | Hybrid $m/cm$ input, Room Templates (L-shape/Square). | Balances IKEA-level precision with setup speed. |
| 03 | **3. 2D Layout** | Drag-and-drop grid, Auto-scaling, Corner handles. | Solves "Spatial Fit Anxiety" through direct control. |
| 04 | **4. 3D Graphics** | One-click 2D-to-3D toggle, Shading, Interactive Camera. | Essential for customer "wow-factor" and walkthroughs. |
| 05 | **5. Customization** | Selective color editing & Global Room Themes. | High-speed aesthetic adjustments during meetings. |
| 06 | **6. Handover** | **Viewer Link Generation** & PDF Export. | Top survey request for remote decision-making. |

---
##  2. Non-Functional Requirements 
*Quality standards and HCI (Human-Computer Interaction) principles.*
- [View](./details/detailed-fr.md)

* **Visibility of Status:** Immediate feedback (Toast notifications) and a **Percentage Loading Bar ($0\% \to 100\%$)** for renders.
* **Error Recovery:** Mandatory **Undo/Redo ($Ctrl+Z$)** and "Confirm Delete" prompts to prevent data loss.
* **Accessibility:** **Adjustable font sizes** for measurements and WCAG-compliant color contrast for store lighting.
* **Efficiency:** **Progressive Disclosure** (hiding advanced tools initially) to solve "Cluttered UI" complaints.
* **Performance:** Low-latency 3D generation to keep customers engaged during live consultations.

