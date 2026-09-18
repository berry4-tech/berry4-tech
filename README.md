# Hi, I'm Sriya 👋

Graduate student at **Northeastern University (MS Information Systems)** with a background spanning software engineering, analyst, and consulting roles. I'm working towards Product Management which means I care about the "why" behind a feature as much as the "how," and I can build the thing myself to test that why.

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

- Classified potentially hazardous asteroids across **958,524 records** from NASA JPL's Small-Body Database, where fewer than 0.2% of asteroids qualify as hazardous — a severe class-imbalance problem
- Designed a two-experiment structure to isolate whether one feature (MOID) was giving models an unfair "answer key," rather than assuming it was safe to use
- Best model (Random Forest, orbital features only) hit **~0.88 recall / ~0.94 PR-AUC**; adding the definitional feature pushed all four models to **≥0.97** across the board, and a depth-4 decision tree ended up reconstructing NASA's own two-condition definition of a hazardous asteroid
- Validated the winning model against the full 958K dataset, not just the 100K sample used for training

`Python` `scikit-learn` `SMOTE` `Data Science`

---

### [Lost & Found Ecosystem — Multi-Enterprise System Design](https://github.com/berry4-tech/GreaterBoston_LostandFound_Ecosystem)
> Java | MongoDB | System Design

- Designed a cross-enterprise system connecting **universities, MBTA, Logan Airport, and law enforcement** around lost-item recovery — 4 organizations, each with their own roles and approval chains
- Built a multi-step work-request approval engine with SLA monitoring and automated routing, so a claim between two universities or from MBTA to an airport follows the right chain of custody
- Designed a dynamic 0-100 trust-score system that adjusts claim eligibility and flags fraud risk based on user behavior

`Java` `MongoDB` `System Design`

---

## What I'm Working On

Building an AI-powered caregiver/medication assistant as a semester-long team project in my "Building AI Apps" course — end-to-end from problem definition and system prompt design through RAG, tool orchestration, security testing, and deployment.

## Let's Connect

Open to Product Manager roles and conversations about AI products, data-informed decisions, or anything above.

[LinkedIn](https://www.linkedin.com/in/sriya-kv/)
