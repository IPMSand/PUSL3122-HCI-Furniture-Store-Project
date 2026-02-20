# 1. Research Findings - Survey >>
**Source:** Raw data from 24 participants (Pro Designers & Homeowners) + IKEA/Planner 5D Benchmarks.

* **Primary UX Pain Point:** "Cluttered Interfaces" and "Spatial Fit Anxiety" (Fear of buying furniture that won't fit).
* **Intuitive Interaction:** 46% of respondents voted **Direct Manipulation (Corner Handles)** as the most natural way to scale.
* **Workflow Preference:** Professionals prioritize **Numerical Dimensions ($m/cm$)** over dragging walls.
* **The "Post-Consultation" Gap:** Homeowners highly requested a **"Viewer Link"** to review designs remotely.
* **Accessibility:** Significant request for **Adjustable Font Sizes** for measurements.

  
# 2. Finalized Functional requirements >>
> After conducting a google form survey with 46 participants + studying competitive already exsting ikea room planner and room planner 5 app.

### 01. Portfolio and Data Manipulation
 _Focus: Efficiency and User Workflow_

| **Requirement**               | **Description**                           | **Rationale / Origin**                                                                |
| ----------------------------- | ----------------------------------------- | ------------------------------------------------------------------------------------- |
| **1.1 Secure Login/Logout**   | Designers access a private dashboard.     | **Requirement:** "Designers must be able to log in to manage their design portfolio." |
| **1.2 Search by Client Name** | Global search bar for all saved projects. | **Survey Priority:** Users requested fast retrieval during live consultations.        |
| **1.3 CRUD Operations**       | Create, Read, Update, and Delete designs. | **Requirement:** "Save, Edit or Delete existing designs."                             |

--
### 02. Room Environment setup
 _Focus: Precision (IKEA) and Flexibility_

| **Requirement**               | **Description**                                          | **Rationale / Origin**                                                       |
| ----------------------------- | -------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **2.1 Hybrid Input System**   | Manual $m/cm$ entry + Shape Templates (L-shape, Square). | **IKEA Planner Influence:** Balances professional accuracy with setup speed. |
| **2.2 Base Environment Spec** | Store size, shape, and initial color scheme.             | **Requirement:** "Enter and store room specifications."                      |            

--

### 03. 2D Design and Layout Engine
 _Focus: Direct Manipulation & Mental Models_

| **Requirement**             | **Description**                                        | **Rationale / Origin**                                                  |
| --------------------------- | ------------------------------------------------------ | ----------------------------------------------------------------------- |
| **3.1 Drag-and-Drop Grid**  | Arrange furniture shapes on a top-down 2D canvas.      | **Requirement:** "Create new designs... in 2D."                         |
| **3.2 Auto-Scaling Engine** | Furniture resizes automatically based on room scale.   | **Requirement:** "Scale furniture items to fit room dimensions."        |
| **3.3 Interactive Handles** | Resize/rotate items using corner "hotkeys" or handles. | **iCanDesign/Survey Choice #1:** Best HCI practice for spatial control. |

--

### 04. 3D Visualizatiob and graphics
 _Focus: Computer Graphics & Realistic Presentation_

| **Requirement**              | **Description**                                       | **Rationale / Origin**                                                   |
| ---------------------------- | ----------------------------------------------------- | ------------------------------------------------------------------------ |
| **4.1 One-Click 3D Toggle**  | Instant conversion from 2D coordinates to 3D space.   | **Initial Requirement:** "Convert designs into 3D views."                |
| **4.2 Global/Local Shading** | Apply shading to individual pieces or the whole room. | **Initial Requirement:** "Apply shading to the entire design."           |
| **4.3 Interactive Camera**   | Orbit, pan, and zoom controls for walkthroughs.       | **HCI Principle:** Provides "Clear Feedback" and engaging visualization. |

--

### 05. Styling and customization 
 _Focus: Aesthetic Consistency_

| **Requirement**                 | **Description**                                | **Rationale / Origin**                                                   |
| ------------------------------- | ---------------------------------------------- | ------------------------------------------------------------------------ |
| **5.1 Selective Color Editing** | Change colors for individual furniture pieces. | **Initial Requirement:** "Change colours for selected furniture pieces." |
| **5.2 Global Room Themes**      | Apply pre-set "Schemes" to the entire design.  | **Survey/Initial Requirement:** "Change colours for the entire design."  |

### 06. Interactive handover
 _Focus: Post-Consultation Experience_

| **Requirement**                | **Description**                                    | **Rationale / Origin**                                            |
| ------------------------------ | -------------------------------------------------- | ----------------------------------------------------------------- |
| **6.1 Viewer Link Generation** | Create a unique URL for customers to view at home. | **Survey Priority:** Ranked as the most desired sharing method.   |
| **6.2 PDF Export**             | Generate a layout summary with dimensions.         | **Industry Standard:** Essential for physical handovers in-store. |


## HCI Design Principles (Handover Advice)

1. **Hick’s Law:** Avoid a "cluttered UI." Use a **Tabbed Menu** (1. Room -> 2. Furniture -> 3. Preview) to limit choices per screen.
2. **Fitts’s Law:** Make common actions like **Undo**, **Save**, and **3D Toggle** large, accessible targets (min 44px) for tablet/touch users.
3. **Nielsen’s 1st Heuristic:** Never show a blank screen during a 3D render. Always show a percentage bar or progressive loading view.

