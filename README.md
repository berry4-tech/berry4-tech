# Hi, I'm Sriya 👋

MS Information Systems student at Northeastern University. I build across full-stack, ML, and AI product surfaces. Working toward Product Management, I care about the "why" behind a feature as much as the "how," and I can build the thing myself to test that why.

---

### Things I've built

- **LabInsight AI** — Full-stack AI healthcare app to analyze lab reports, get health insights, and connect with doctors. [Code](https://github.com/berry4-tech/LabInsightsAI)
- **Orbital Threat Assessment** — ML pipeline classifying hazardous asteroids from NASA JPL data, with SMOTE and stratified CV to handle severe class imbalance. [Code](https://github.com/berry4-tech/Orbital_Threat_Assessment)
- **Lost & Found Ecosystem** — Multi-enterprise Java app connecting Boston universities, MBTA, and airports for lost & found, with trust-score fraud detection. [Code](https://github.com/berry4-tech/GreaterBoston_LostandFound_Ecosystem)

---

### Tech I work with

**Languages**
![Languages](https://skillicons.dev/icons?i=java,python,js,ts,cpp&perline=8)

**Frameworks & Libraries**
![Frameworks](https://skillicons.dev/icons?i=react,nodejs,flask&perline=8)

**Databases & Tools**
![Databases & Tools](https://skillicons.dev/icons?i=mongodb,git,github&perline=8)

---

## Featured Projects

### [LabInsight AI — AI-Powered Lab Report Analysis Platform](https://github.com/berry4-tech/LabInsightsAI)
> React | TypeScript | Node.js | MongoDB | RAG (Groq/Llama 3.3 70B)

- Built a full-stack healthcare platform spanning **4 distinct user roles** (patient, doctor, admin, and system), each with its own dashboard and permission scope
- Owned the admin and doctor-facing product surfaces on a 4-person team, including the patient-doctor connection workflow and role-based access control
- Integrated a **RAG-powered chatbot** that answers health questions using context pulled from the user's own uploaded reports, backed by a Python/Flask microservice with sentence-embedding retrieval
- Implemented secure auth (JWT + bcrypt + Google OAuth) and documented the full API with Swagger

`React` `TypeScript` `Node.js` `MongoDB` `RAG` `Flask`

---

### [Orbital Threat Assessment — Hazardous Asteroid Classification](https://github.com/berry4-tech/Orbital_Threat_Assessment)
> Python | scikit-learn | SMOTE | NASA JPL Data

- Built a stratified ML pipeline to detect potentially hazardous asteroids (PHAs) across NASA JPL's Small-Body Database, addressing a severe **449:1 class imbalance**
- Applied SMOTE oversampling, StandardScaler normalization, and **5-fold StratifiedKFold cross-validation** across four models: Logistic Regression, Decision Tree, Random Forest, and LinearSVC
- Best model reached **PR-AUC of 0.988**, and a depth-4 decision tree ended up reconstructing NASA's own two-condition definition of a hazardous asteroid
- Designed a two-experiment structure to isolate whether one feature (MOID) was giving models an unfair "answer key," rather than assuming it was safe to use

`Python` `scikit-learn` `SMOTE` `Data Science`

---

### [Lost & Found Ecosystem — Multi-Enterprise System Design](https://github.com/berry4-tech/GreaterBoston_LostandFound_Ecosystem)
> Java | MongoDB | System Design

- Designed a cross-enterprise system connecting **universities, MBTA, Logan Airport, and law enforcement** around lost-item recovery — 4 organizations, each with their own roles and approval chains
- Built a multi-step work-request approval engine with SLA monitoring and automated routing, so a claim between two universities or from MBTA to an airport follows the right chain of custody
- Designed a dynamic 0-100 trust-score system that adjusts claim eligibility and flags fraud risk based on user behavior

`Java` `MongoDB` `System Design`

---

## Patents

Co-inventor on two patents filed during my time at Trispace Technologies:
- **GPU cost/power optimization** for hardware efficiency (#537663)
- **BOM cost/power optimization** in drone systems (#582124)

## What I'm Working On

Building an AI-powered caregiver/medication assistant as a semester-long team project in my "Building AI Apps" course — end-to-end from problem definition and system prompt design through RAG, tool orchestration, security testing, and deployment.

## Let's Connect

Open to Product Manager roles and conversations about AI products, data-informed decisions, or anything above.

[LinkedIn](https://www.linkedin.com/in/sriya-kv/)

![Profile views](https://komarev.com/ghpvc/?username=berry4-tech&label=Profile%20views&color=6f42c1&style=flat)
