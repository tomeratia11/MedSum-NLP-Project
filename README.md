##  MEDSUM - Longitudinal Medical Summarization Model

A clinical NLP system designed to generate clear, structured, and chronological **Patient Journey Summaries** from fragmented medical records.

MEDSUM processes multi-source clinical texts, extracts key medical events, aligns them on a timeline, and generates a concise 3–7 sentence narrative describing the patient’s medical course.

---

##  Overview

Modern medical records are spread across multiple unstructured sources:

- Clinic visit notes  
- Doctor–patient messages  
- ER reports  
- Lab and imaging summaries  
- Scanned handwritten documents  

This fragmentation makes it difficult for clinicians to obtain a quick, reliable understanding of a patient’s history, leading to missed information and inefficient decision-making.

**MEDSUM** aims to address this problem with an end-to-end summarization pipeline.

---

##  Project Goal

Create a system that summarizes a patient’s longitudinal medical history into one coherent narrative describing:

- Diagnoses  
- Treatments  
- Key clinical events  
- Disease progression  
- Current status  

The output is a short, clinically meaningful **Patient Journey Summary**.

---

##  Input & Output

### **Input**
A chronological collection of patient-related clinical texts:

- Visit notes  
- Physician messages  
- ER documentation  
- Lab and imaging reports  
- Other structured or unstructured clinical sources  

### **Output**
A concise **3–7 sentence summary** capturing the full clinical course.

---

##  Key Features & Contributions

✔ Multi-document clinical summarization  
✔ Event extraction → Structuring → LLM summarization  
✔ Handling mixed document formats (digital, scanned, handwritten)  
✔ Long-context modeling for longitudinal narratives  
✔ Synthetic data for rare or incomplete clinical scenarios  

This project brings together **GenAI, medical NLP, and temporal event modeling** to tackle a real problem in clinical decision support.

---

##  Project Structure (coming soon)

```
/data
/src
/models
/notebooks
/app
```

---

## Status
Early development phase.  
Additional modules will be added as the project progresses.

---

##  Future Work

- Advanced timeline alignment  
- Evaluation using medical summarization metrics  
- Structured output formats (FHIR/JSON)  
- Synthetic augmentation for rare clinical conditions  

---
