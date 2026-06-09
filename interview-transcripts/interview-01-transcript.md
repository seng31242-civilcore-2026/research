# Fact-Finding: Structured Interview Transcript (Field Supervisor)

## 1. Interview Metadata
*   **Date Conducted:** 2026-05-19
*   **Interviewer:** Mr. Kasun Nadeera
*   **Interviewee:** Mr. Dinesh
*   **Target Persona:** Supervisor (Mobile App User)
*   **Objective:** Understand the daily reporting routine, environment constraints (e.g., internet access), and asset request workflow to ensure the app meets the "under 5 minutes" success criterion.

---

## 2. Key Findings Summary
*   **Primary Pain Point:** Primavera P6 is too complex for mobile use on-site.
*   **Offline Mode is Critical:** Internet connectivity is highly unreliable deep inside the construction site. Local caching and auto-sync are required.
*   **Required Inputs for Daily Report:** Tasks completed (linked to BOQ), materials/equipment used, labour count and hours, weather, and geo-tagged photos.
*   **Separate Workflows Identified:** "Asset Requests" (needed for the next day) and "Material Delivery Logs" (arriving from suppliers) must be distinct from the daily usage report.
*   **Issue Reporting:** Supervisors need a dedicated snag/issue log to capture and send geo-tagged photos of site problems directly to managers.

---

## 3. Interview Transcript

**Interviewer:** Hello Mr. Dinesh. Thank you for your time today. We are building the CivilCore mobile app to replace Primavera P6, which we know is too complex for the field. I want to ask a few questions about your daily routine to make sure the new app is easy to use.

**Mr. Dinesh:** Hello! Yes, I am happy to help. Primavera P6 is too hard to use on my phone while I am on the site. I need something much simpler.

**Interviewer:** I understand. Our goal is for you to be able to finish your daily report in under 5 minutes on your mobile phone. What exactly do you need to write down at the end of every day?

**Mr. Dinesh:** I need to write down the tasks we finished that day. I also have to record the materials and equipment we used, the number of workers on site (both skilled and unskilled), their working hours, and the weather condition.

**Interviewer:** Great. In the new app, the tasks will be linked directly to the Bill of Quantities (BOQ), so you can just pick them from a list instead of typing them out. Do you also need to take photos of the work?

**Mr. Dinesh:** Yes, taking photos is very important to show our progress.

**Interviewer:** We will add a feature to take photos that are automatically geo-tagged with your location. Now, what about the internet connection on the construction site? Do you always have data?

**Mr. Dinesh:** No, the internet is very bad. Often, we have no signal at all when we are working deep inside the site.

**Interviewer:** That is very good to know. We will build an "Offline Mode." This means you can fill out your whole report without the internet, and the app will automatically sync the data later when you get a connection.

**Mr. Dinesh:** That would be perfect.

**Interviewer:** How do you currently ask for materials or equipment for the next day?

**Mr. Dinesh:** Right now, I have to call or message the manager. It would be great if the app could handle this.

**Interviewer:** It will! We are building an "Asset Request" feature. You can select the item, the amount you need, and the date you need it. The manager can then approve it from their web dashboard. Also, what happens when new materials arrive on the site from a supplier?

**Mr. Dinesh:** I need to record what arrived, how much. This is different from the materials we actually use that day.

**Interviewer:** Understood. We will make a separate "Material Delivery Log" for arriving materials. Finally, what do you do if you find a problem or a broken item on the site?

**Mr. Dinesh:** I usually call the manager, but it is hard to explain without showing them.

**Interviewer:** For that, we will include an "Issue Log." You can flag a problem, take a photo, and send it directly to the manager to fix and close.

**Mr. Dinesh:** This sounds exactly like what we need. It will save me a lot of time every evening.

**Interviewer:** Thank you, Mr. Dinesh. Your answers are very helpful for our design!

---
*Documented by: Mr. Kasun Nadeera
