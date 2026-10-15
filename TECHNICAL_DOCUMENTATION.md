# Software Development Technical Documentation
## Computer Registration System
**Institution:** Nueva Vizcaya State University (NVSU), Bayombong Campus  
**Status:** Student prototype / documentation draft

## 1. Project Title
Computer Registration System

## 2. Short Description
The Computer Registration System is a proposed web-based system for organizing computer laboratory registration and monitoring at NVSU, Bayombong Campus. Manual recording can make records harder to organize and review. This prototype allows a user to submit a laboratory visit request and lets a demonstrator search records, update a request status, and export records. Final requirements should be confirmed with intended users.

## 3. Proposed SDLC Model
The proposed model is the Waterfall Model. Confirm that this is the model required by your instructor and revise this section if your group selects another model.

### Phase 1 – Planning and Requirements Analysis
Identify problems in the current laboratory registration and monitoring process. Gather requirements from intended users, such as students and laboratory personnel. Define the objectives, scope, required information, and features before development.

### Phase 2 – System Design
Plan the interface and how users move between pages. Balsamiq can be used to create wireframes for the dashboard, registration form, and records page. Include screenshots of your actual Balsamiq designs if required by the instructor. The included HTML interface is a working prototype, not a Balsamiq file.

### Phase 3 – Implementation of Code
The prototype uses HTML5 for page structure, CSS3 for styling, and JavaScript for interactions. Browser localStorage keeps demo records in the current browser. GitHub stores the source files and their history. A real system would need a secure backend, shared database, authentication, and access controls.

### Phase 4 – Testing and Deployment
Test required form fields, registration submission, record display, search, status updates, deletion, and CSV export. Record the actual result of each test after performing it. If required, deploy the static files to a suitable host after testing. Deployment is not complete until a working public link has been created and checked.

**Testing checklist (fill in after testing):**

| Test | Expected result | Actual result |
|---|---|---|
| Submit a complete registration | Record appears in the records list | Not tested yet |
| Leave a required field blank | Browser prevents submission | Not tested yet |
| Search by name or ID | Matching records appear | Not tested yet |
| Change status | Status and dashboard counts update | Not tested yet |
| Delete a record | Record is removed after confirmation | Not tested yet |
| Export CSV | CSV file downloads | Not tested yet |
| Refresh the page | Records remain in the same browser | Not tested yet |

### Phase 5 – Maintenance
The system should be reviewed regularly to make sure its features continue to work. Reported problems should be recorded and fixed, and updates should be tested before release. The team should revise the system when approved requirements change. For a future production version, authorized personnel should also manage backups, security updates, database maintenance, and access permissions. The current prototype stores records only in one browser, so records are not centrally backed up or shared.

## 4. Prototype – User Interface
The prototype includes:
- **Dashboard:** shows total, pending, and approved registration counts.
- **Register a Visit:** collects student details, laboratory room, date, time slot, purpose, and optional notes.
- **Registration Records:** allows searching, filtering by status, updating status, deleting demo entries, and exporting records to CSV.

If your instructor requires Balsamiq specifically, recreate the main screens in Balsamiq and add screenshots to your final documentation.

## 5. Technology Stack
- HTML5 — page structure
- CSS3 — responsive layout and styling
- JavaScript — form and record interactions
- Browser localStorage — demo-only storage in one browser
- GitHub — source-code repository and version history
- GitHub Pages or another static host — optional hosting for this front-end prototype

## 6. Repository and How to Run
Open `index.html` in a modern browser, or use a local development server such as VS Code Live Server. The prototype does not require package installation.

## 7. Limitations and Future Improvements
This is a front-end prototype only. It does not have secure login, a central database, shared multi-user access, or role-based permissions. Demo data is saved only in the current browser. Use fictional data and do not enter real student personal information. Future improvements may include secure authentication, a backend database, role-based access, and approved computer availability tracking.
