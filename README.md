# Medi-Sync Family Dashboard 🏥

**A "Calm Technology" solution for the Sandwich Generation.**
*Reduce mental load. Centralise care. Bridge the gap between medical needs and domestic reality.*

🔴 **[View Live Demo](https://nicola-empower.github.io/medi-sync-demo/)**

---

## 📖 Project Overview

**Medi-Sync** is a conceptual Progressive Web App (PWA) designed to manage the complex logistics of family caregiving.

It was built to solve a specific problem: **The "Recall Audit."**
When caring for a child with complex needs or an elderly relative, carers are often exhausted, yet they are expected to remember exact medication times, incident details, and domestic tasks. Standard messaging apps (WhatsApp) are too chaotic for this data, and medical apps are often too clinical and narrow.

**The Solution:** A shared "Command Centre" that tracks:
1.  **Medical Routine:** Medications and Vitals.
2.  **Critical Incidents:** Seizures, falls, and mood changes (with detailed context).
3.  **Domestic Logistics:** Who cooked dinner? Is the washing done? What groceries are needed?

##  Key Features

### 1. Trauma-Informed UI ("Calm Tech")
* **Glassmorphism Design:** A "Sage & Slate" palette with frosted glass effects provides a calming, non-clinical user experience.
* **Hidden Complexity:** High-stress input fields (e.g., Seizure Reports) are hidden behind modals. The user is not bombarded with scary questions unless they initiate an alert.

### 2. Complex State Simulation (Vanilla JS)
* **Real-Time Feed:** Actions (toggling a pill, logging a mood) are timestamped and injected into a live activity stream.
* **Dynamic Modals:** "Seizure" and "Fall" reports capture multi-point data (Duration, Loss of Consciousness, Injury) and render distinct "Alert Cards" in the timeline.
* **Persistent Lists:** A functional shopping list and doctor's notepad that simulates a shared database.

### 3. The "Domestic Bridge"
* Unlike purely medical apps, Medi-Sync includes a "Handover" section for tracking household chores (laundry, meals), bridging the gap between healthcare and home life.

---

##  Tech Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **Styling:** CSS Variables, Flexbox/Grid, Backdrop-Filter (Glass effect).
* **Icons:** FontAwesome 6.
* **Deployment:** GitHub Pages.

---

##  How to Run Locally

This project is built as a lightweight, single-file solution for demonstration purposes.

1.  Clone the repository:
    ```bash
    git clone [https://nicola-empower.github.io/medi-sync-demo/](https://nicola-empower.github.io/medi-sync-demo/)
    ```
2.  Navigate to the project folder.
3.  Open `index.html` in any modern web browser.

---

##  Design Philosophy: The "Why"

> *"I didn't design this based on a theory; I designed it based on survival."*

This project explores the intersection of **User Experience (UX)** and **Cognitive Load**. The target demographic is the "Sandwich Generation": adults caring for young children and ageing parents simultaneously.

By combining domestic tasks with medical tracking, the application reduces the friction between siblings/carers and creates a "Source of Truth" for the patient's care history.

---

##  Author

**Nicola Berry | Empower Digital Solutions**

* **Website:** [empowerdigitalsolutions.co.uk](https://empowerdigitalsolutions.co.uk)
* **Service:** Custom Dashboards & Business Automation

---
*© 2025 Empower Digital Solutions. All Rights Reserved.*
