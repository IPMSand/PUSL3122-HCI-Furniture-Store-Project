<!-- User Stories mapped to Persona: Thushara (Designer) -->

# User Stories — Designer (Thushara)

### US-D1
**User Story:** As Thushara, I want to type exact room dimensions (e.g., 5.0m x 4.0m) so that I can set up an accurate floor plan quickly while a client is waiting.  
**Acceptance Criteria:**  
- System accepts numerical input for length, width, and height.  
- Room outline is generated within 3 seconds.  
- Input validation prevents negative or unrealistic dimensions.  

### US-D2
**User Story:** As Thushara, I want to modify a standard template by dragging wall segments so that I don't have to draw irregular room shapes from scratch.  
**Acceptance Criteria:**  
- Drag handles are visible on walls.  
- Dragging reshapes the room in real time.  
- System prevents walls from overlapping or creating invalid shapes.  

### US-D3
**User Story:** As Thushara, I want to see a progress bar while the 3D model loads so that I know the system is working and doesn’t think it has frozen.  
**Acceptance Criteria:**  
- Percentage bar (0–100%) appears immediately when loading starts.  
- Updates smoothly until the model is fully generated.  
- Option to cancel loading if needed.  

### US-D4
**User Story:** As Thushara, I want to export the finished design as a PDF so that I can email it to the client straight after our meeting.  
**Acceptance Criteria:**  
- 'Export as PDF/Image' button is clearly visible.  
- Exported file includes 3D view, measurements, and applied colors.  
- Export completes within 5 seconds for standard rooms.

- ---
<!-- User Stories mapped to Persona: Mohammed (Customer) -->

# User Stories — Customer (Mohammed)

### US-C1
**User Story:** As Mohammed, I want to select a pre-set room template (L-shape, square, rectangle) so that I don't have to configure the room shape manually.  
**Acceptance Criteria:**  
- The gallery of templates is shown at the start.  
- Selecting a template instantly creates the room outline.  
- No further input needed.  

### US-C2
**User Story:** As Mohammed, I want the salesperson to control the design screen while I watch so that I can focus on giving my opinion without feeling overwhelmed.  
**Acceptance Criteria:**  
- Interface supports 'presenter mode'.  
- One person navigates while the client observes.  
- Mirrored or shared screen works without extra login.  

### US-C3
**User Story:** As Mohammed, I want a pop-up confirmation before anything is deleted so that I don't lose my design by accident.  
**Acceptance Criteria:**  
- Every delete triggers a confirmation dialog.  
- Cancel and Confirm buttons available.  
- Undo option is also available if deletion occurs.  

### US-C4
**User Story:** As Mohammed, I want to receive a viewer link after the session so that I can review the 3D design with my family at home before making a purchase.  
**Acceptance Criteria:**  
- Shareable link generated from completed design.  
- Opens read-only 3D view.  
- No login required.

- ---

<!-- User Stories mapped to Persona: Sara (Youth) -->

# User Stories — Youth (Sara)

### US-Y1
**User Story:** As Sara, I want to drag walls on a finger-friendly grid so that I can set up my room shape without typing any dimensions.  
**Acceptance Criteria:**  
- Wall segments respond to touch/drag on a visible grid.  
- Room outline updates in real time.  

### US-Y2
**User Story:** As Sara, I want to apply a full-room color theme (e.g., Modern Blue) in one tap so that I can quickly visualize different styles.  
**Acceptance Criteria:**  
- 'Global Theme' panel shows preset color schemes.  
- Selecting one applies matching colors to all furniture and walls instantly.  

### US-Y3
**User Story:** As Sara, I want a clearly visible Undo button on the screen so that I can fix mistakes without searching through menus.  
**Acceptance Criteria:**  
- Undo button permanently visible in toolbar.  
- Tapping reverses the last action with a confirmation animation.  

### US-Y4
**User Story:** As Sara, I want to share my design as a viewer link so that I can send it to friends on messaging apps.  
**Acceptance Criteria:**  
- 'Share' button generates a short link.  
- Link opens read-only 3D view in any browser without login.

- ---
<!-- User Stories mapped to Persona: Kamal (Elderly) -->

# User Stories — Elderly (Kamal)

### US-E1
**User Story:** As Kamal, I want to enter room dimensions by typing numbers so that I can use the exact measurements I already know from measuring my bedroom.  
**Acceptance Criteria:**  
- Simple numeric input fields accept dimensions in meters.  
- The room is drawn automatically with a labeled diagram.  

### US-E2
**User Story:** As Kamal, I want all measurement labels and menu text to be displayed in a large, readable font so that I don't have to strain to read the screen.  
**Acceptance Criteria:**  
- All text defaults to a minimum 14pt.  
- 'Increase Font Size' toggle is visible on the home screen.  

### US-E3
**User Story:** As Kamal, I want a high-contrast display mode so that I can clearly distinguish buttons and furniture labels on my screen.  
**Acceptance Criteria:**  
- High-contrast toggle available.  
- Enabling it switches to dark-background / white-text / bold-icon theme.  

### US-E4
**User Story:** As Kamal, I want a loading animation with a time estimate so that I know the design is still being prepared and I haven't lost my work.  
**Acceptance Criteria:**  
- 3D model loading shows spinning animation with countdown (e.g., "About 15 seconds") in the center of the screen.
