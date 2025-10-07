# 🎓Futurize -- University Application Prep Platform

Futurize is a platform designed to help South African students **prepare for university applications**.  
The app focuses on readiness, guidance, and engagement through **APS calculators, gamification, and application tracking**.  

---

## 🚀 Features

- **APS Calculator** – Quickly calculate your Admission Points Score.  
- **Eligibility Checker** – Compare APS against program requirements.  
- **Application Tracking** – Dashboard to track multiple university applications in one place.  
- **Document Upload (MVP)** – Store and organize required documents for submissions.  
- **Gamification** – Levels, streaks, badges, and progress indicators to keep students motivated.  
- **Career Roadmaps** – Guidance for university programs, alternative certifications, vocational training, and upskilling opportunities.  
- **Sorting Hat** – Classify learners into fun categories or titles (e.g., Science Explorer, Creative Thinker) to guide pathways and add community engagement.  
- **Suggested Programs** – Recommend study options based on interests, APS score, and budget constraints.  
- **Cost Comparison** – Suggest alternative institutions or programs based on affordability.  
- **Browser Extension (Core Feature)** – Autofill online university/vocational application portals with stored data, making applications seamless without switching back and forth.  


---

## 🛠 Tech Stack

### Frontend (Web Prototype)
- **Framework:** React + Vite  
- **Styling:** TailwindCSS  
- **Icons:** Lucide React  
- **Animations:** Framer Motion  

### Mobile App
- **Framework:** Flutter (cross-platform for iOS & Android)  
- **State Management:** Provider / Riverpod (TBD by team)  
- **Storage:** Secure local storage (e.g., Hive, SharedPreferences) with optional cloud sync  

### Browser Extension
- **Platform:** Chrome Extension (Manifest V3)  
- **UI Framework:** Angular/React (for popup/dashboard)  
- **Integration:** Content scripts + background service worker  
- **Features:** Autofill forms, application tracking, quick shortcuts  

### Backend & Services (Future Consideration)
- **Authentication:** Firebase Auth / Supabase (TBD)  
- **Database:** Firestore / Supabase / PostgreSQL (depending on scalability needs)  
- **File Storage:** Firebase Storage / Google Drive API (for documents)  


---


## 👥 Contributors
Nqobile Mthombeni, Karabo Sithole and Sinomtha Mzamo
