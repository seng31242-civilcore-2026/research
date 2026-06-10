# Fact-Finding: Document Analysis (BOQ)

## 1. Document Analysis Metadata
*   **Date Conducted:** 2026-05-19
*   **Analyst:** Mr. Nalindu Ashirwada
*   **Objective:** To analyze the current Bill of Quantities (BOQ) used by the client and identify the exact data fields required to import these work items into the CivilTrack system as trackable tasks.

---

## 2. List of Documents Reviewed
As required by the fact-finding methodology, the following sample documents were provided by the client and analyzed:
1.  **`BOQ Final.xlsx`**  (Bill of Quantities)
2.  **`Programme.xlsx`**  (Track task progress)
3.  **`Project Costing.xlsx`**  (Estimate project cost)
4.  **`Quotation.xlsx`**  (Estimate project cost and quantities)

---

## 3. Key Data Extracted
By reviewing the documents above, we have determined that every BOQ line item contains the following critical data fields that must be captured by our database's **Task** entity:
*   **Work Item Description:** The actual name/description of the task (e.g., "Excavation of topsoil", "Pouring Grade 20 Concrete").
*   **QTY:** The measurement unit used for the task (e.g., cubic meters (m^3), square meters (m^2), or linear meters).
*   **Amount:** The total amount of cost that work approved in the contract for that specific unit.
*   **Rate:** The financial cost per unit (used by managers to calculate overall project cost against the budget).

---

## 4. System Implications & Business Logic
*   **BOQ to Task Linking:** When a manager sets up a new project, each line item from the BOQ will  be a "Task". 
*   **Progress Calculation:** Field supervisors will report their daily completed quantity against these specific tasks. The system will then calculate the total project completion percentage by comparing the reported daily quantities against the Planned Quantity(QTY) extracted from the original BOQ.

---
*Documented by: Mr. Nalindu Ashirwada
