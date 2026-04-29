# Dynamic Syllabus Authoring & PDF Generator

🚀 Django Semi-Hackathon: SIRIUS
📋 Project Details
Theme: Dynamic Syllabus Authoring & PDF Generator
Team Members:
Pranav Bharadwaj M
Mohammad Aun Rizvi
Kartik S Rathod
Pradyumna HN
Kumar Saurya
Live URL: (To be added after deployment)

🎯 Project Overview
This project addresses inefficiencies in manual syllabus creation by providing a Dynamic Syllabus Authoring System that automates syllabus generation, CO–PO mapping, and PDF export in a standardized university format.

Manual processes are replaced with structured forms, dynamic modules, and automated workflows, significantly improving accuracy and efficiency.

❗ Problem Statement
Manual syllabus creation is error-prone
No standardized metadata format
Difficult to manage modules and experiments
CO–PO mapping is complex
PDF generation is inconsistent and time-consuming

💡 Solution
Structured syllabus metadata input
Dynamic module & experiment management (AJAX)
Automated CO–PO mapping using JSON
University-format PDF generation using HTML + CSS

🧰 Tech Stack
Backend
Django
Python
Frontend
Bootstrap 5
Django Templates
Database
SQLite
Libraries
Pillow
django-crispy-forms
gunicorn
whitenoise
weasyprint (for PDF generation)

✨ Key Features
📄 Syllabus Metadata Form with validation
🔄 Dynamic module management (add/remove without reload)
📊 CO–PO mapping system (H/M/L levels using JSON)
🖨️ Pixel-perfect PDF generation
📱 Responsive UI for all devices

🧩 Modules
Course Metadata Management
Module & Experiment Configuration
Admin Dashboard for syllabus control

🎯 CO-SDG Mapping Table
Course Outcome	How This Project Demonstrates It	SDG Target Addressed
CO1: MVT Architecture	Implements Django MVT architecture with structured views, templates, and models	SDG 4.5
CO2: Models & Forms	Uses Django models and forms for syllabus metadata and validation	SDG 9.5
CO3: Dynamic UI	AJAX-based dynamic module addition/removal	SDG 9.1
CO4: Data Handling	JSON-based CO–PO mapping system	SDG 4.7
CO5: Deployment	Cloud deployment using Render	SDG 9.5

🌍 SDG Justification (150 words)
This project contributes to Sustainable Development Goal 4 (Quality Education) by improving the efficiency and standardization of syllabus creation in educational institutions. Traditional manual syllabus creation is prone to errors, inconsistencies, and delays, which negatively impacts teaching quality and curriculum alignment. By introducing an automated system with structured data input, validation mechanisms, and dynamic module management, the project ensures accurate and consistent syllabus generation.
Additionally, the automated CO–PO mapping enhances curriculum design by aligning course outcomes with program outcomes effectively. The system also supports SDG 9 (Industry, Innovation, and Infrastructure) by leveraging modern web technologies to digitize and streamline academic workflows. Overall, this solution reduces manual workload for faculty, improves productivity, and ensures standardized academic documentation, ultimately enhancing the quality of education delivery.
