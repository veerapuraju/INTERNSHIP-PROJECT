# INTERNSHIP-PROJECT
Robust OCR for Skewed and Distorted Text in Agro-Product Labels


📘 Robust OCR for Skewed and Distorted Text in Agro-Product Labels
This repository contains the research, dataset summary, and implementation overview for an AI-powered OCR system designed to recognize and extract text from skewed, rotated, and distorted agro-product labels under challenging real-world conditions.

🔍 Project Overview
Agro-product labels often contain critical information like expiry dates, usage instructions, and certification marks. However, these labels are frequently photographed in suboptimal conditions—skewed angles, poor lighting, and varying fonts/languages—making OCR difficult.

This project addresses these challenges by developing an end-to-end deep learning OCR pipeline using:

🧠 EAST (Efficient and Accurate Scene Text Detector) for robust text localization

🔁 Geometric transformations for skew and perspective correction

📖 TrOCR (Transformer-based OCR) for multilingual text recognition

🗃️ A custom-labeled dataset of 3,500+ agro-product images annotated for text detection and recognition tasks

🛠️ Key Features
Real-world dataset with skewed, curved, and low-light images

Support for 6 Indian languages: English, Hindi, Telugu, Tamil, Marathi, Bengali

Skew correction using affine and perspective transformations

High recognition accuracy: CER = 2.9%, WER = 5.8%

Output refinement using domain-specific language models and post-processing

📌 Applications
Smart agriculture and agri-retail automation

Product traceability and regulatory compliance

Rural digitization and supply chain transparency
