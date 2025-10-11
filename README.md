# Sustainability Intelligence Platform (SIP)
### JunctionX Vaasa 2025 – Wärtsilä Challenge  
*Team Fibers:* Bilal Moussaoui El Azrak · Xinshen Xiang Chen · Pau López Pujals · Anouar El Haddadi El Yahyati  

## About the project

*SIP (Sustainability Intelligence Platform)* is a web application we built during *JunctionX Vaasa 2025, under the **Wärtsilä Challenge*.  
Our goal was simple: make sustainability reporting less painful and more meaningful for companies.

Today, many businesses collect tons of environmental data — energy use, logistics, materials — but struggle to turn it into something useful. We wanted to change that.  
SIP takes raw activity data and automatically generates insights about carbon footprint, eco-costs, and ESG classifications, following the official *ESRS environmental standards (E1–E5)*.

It’s fast, transparent, and designed to make sustainability measurable.

<br>

## What it does

- *Uploads your data:* You can drop a CSV file with your company’s activities (e.g. energy use, fuel, materials).  
- *Understands it:* The system parses and maps everything to pollutants and impact categories.  
- *Thinks for you:* A small AI model classifies each activity under ESRS standards.  
- *Shows results clearly:* The web dashboard displays carbon emissions, eco-costs, and compliance indicators — all in one place.

The goal was not just to make a report generator, but a real assistant for sustainability teams.

<br>

## Architecture
The backend does all the logic and computation, while the frontend focuses on clarity and real-time feedback.

### Software Diagram

![Architecture Diagram](architecture_diagram.png)

### FrontEnd Interface
![Application Interface](interface.png)

###  Technologies we used

| Area | Stack |
|------|-------|
| Frontend | React, TypeScript, TailwindCSS |
| Backend | Python, Django, Django REST Framework |
| AI & Data | Pandas, NumPy, Scikit-learn |
| Tools | Docker, Git, VS Code |
| Standards | ESRS (E1–E5), CO₂ equivalency tables |


###  How it works (example)

*Input CSV*

csv

activity,quantity,unit
Electricity consumption, 2000, kWh
Diesel used in transport, 150, L
Plastic packaging, 50, kg
