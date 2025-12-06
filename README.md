# Personal Health Assistance Application

A comprehensive Streamlit-based web application providing educational health information, doctor recommendations, and medical product catalog through voice-enabled interface and responsive UI design. [file:1][file:3]

[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)

## Project Overview

This application serves as an educational tool for accessing general health information covering 50+ medical conditions, including personalized recommendations for medication, yoga practices, dietary guidelines, and general wellness advice sourced from `dataset.csv`. Key functionalities include voice input processing, doctor database lookup, medical shopping cart, and educational content delivery with local data persistence. [file:1][file:2][file:3]

## Core Features

| Module | Functionality |
|--------|---------------|
| **Voice Interface** | Speech-to-text conversion for name, age, and condition input via browser microphone |
| **Health Database** | 50+ conditions with medication, yoga, diet, and advice recommendations [file:3] |
| **Doctor Directory** | Condition-specific specialist listings with contact information |
| **Product Catalog** | Medical supplies inventory (thermometers, monitors, PPE) with shopping functionality |
| **Educational Content** | Medical facts, wellness riddles, and inspirational quotes |
| **Data Management** | Local CSV storage (`patients_data.csv`, `shoperslist.csv`) ensuring privacy |

## Technical Implementation

### System Architecture
├── app.py # Primary Streamlit application (22,236 lines)​
├── dataset.csv # Medical condition database (9,323 bytes)​
├── patients_data.csv # Patient consultation history​
├── shoperslist.csv # Shopping transaction records
└── requirements.txt # Python dependencies

text

### Technology Stack

| Component | Technology |
|-----------|------------|
| Frontend Framework | Streamlit with custom CSS styling |
| Voice Processing | streamlit-micrecorder, pyttsx3 text-to-speech |
| Data Processing | pandas for CSV operations |
| Storage | Local file system (CSV format) |
| Deployment | Streamlit Cloud / GitHub Pages compatible |

## Deployment Instructions

Prerequisites: Python 3.8+
git clone https://github.com/YOUR_USERNAME/voice-health-assistant.git
cd voice-health-assistant
pip install -r requirements.txt
streamlit run app.py

text

**Access URL**: `http://localhost:8501`  
**Browser Requirements**: Microphone permissions required for voice functionality

## Sample Usage Scenarios

### Case Study 1: Fatty Liver Consultation [file:2]
Patient: Amit Sharma, Age 19
Input: "Fatty Liver"
Recommendations:

Medications: Lifestyle modification

Yoga: Bhujangasana

Diet: Low fat, high fiber

Advice: Avoid alcohol consumption

text

### Case Study 2: Malaria Information [file:3]
Recommendations:

Medications: ACTs + paracetamol (consult physician)

Yoga: Anulom Vilom post-recovery

Diet: Khichdi, coconut water, easily digestible foods

text

## Data Privacy & Security

- **Local Storage Only**: All patient data stored in `patients_data.csv` on user device
- **No Cloud Transmission**: Zero data upload to external servers
- **No Authentication Required**: Anonymous usage without account creation
- **CSV Format**: Transparent, editable data storage [file:1][file:2]

## Dataset Coverage [file:3]

**Medical Conditions (50+)**: Cold, Fever, Cough, Influenza, Asthma, Pneumonia, Tuberculosis, COVID-19, Diabetes, Hypertension, High Cholesterol, Obesity, Thyroid Disorders, Vitamin Deficiencies, Anemia, Gastrointestinal disorders, Skin conditions, Infectious diseases (Dengue, Malaria, Typhoid), Neurological conditions, Cardiovascular diseases.

## Contribution Guidelines

1. **Dataset Expansion**: Add conditions following `Disease,Medicines,Yoga,Diet,Advice` format in `dataset.csv`
2. **Voice Enhancement**: Improve speech recognition accuracy for regional accents
3. **Product Catalog**: Expand medical supplies inventory
4. **UI Improvements**: Enhance responsive design and accessibility

## 🛑 Legal & Medical Disclaimer

**CRITICAL NOTICE**: This application is developed **SOLELY FOR EDUCATIONAL AND DEMONSTRATION PURPOSES**.

### ⚠️ Non-Medical Use Only
- **NOT a medical diagnosis tool**
- **NOT a treatment recommendation system**
- **NOT a substitute for professional medical advice**
- **NOT intended for emergency medical situations**

### 📋 Legal Limitations
1. All health information is **general educational content only**
2. Medication, yoga, and diet suggestions are **informational references**
3. Users **MUST consult licensed healthcare professionals** for any medical condition
4. Developer assumes **no liability** for health decisions made using this application
5. In case of medical emergency, **contact qualified emergency services immediately**

### 🔒 Data Responsibility
- Users are responsible for data stored locally on their devices
- No personal data collection or transmission occurs
- Backup patient data (`patients_data.csv`) recommended

## Support Contact

**Amit Sharma**  
*Artificial intelligence student *  
📧 support@yourhealthassistant.com  
📞 +91 972345670 *(Support hours: Mon-Fri, 9 AM - 6 PM IST)*

---

**Repository maintained for academic and portfolio demonstration purposes only.** 
