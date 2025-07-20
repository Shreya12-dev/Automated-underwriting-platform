# Automated Underwriting Platform 

This is an AI-powered system that automates property risk assessment by analyzing documents and images.

 Features
- Extracts property details from PDF reports
- Detects damage from property images using computer vision
- Calculates risk scores based on custom rules
- Optional web app with Streamlit

Tech Stack
- Python, PyMuPDF, spaCy, OpenCV, YOLOv8, Streamlit

 Sample Inputs
- 📄 Property Report PDFs
- 🖼️ House Images with/without damage

How to Run
Run `colab_notebook.ipynb` to test backend.
Run `app.py` using:
```bash
streamlit run app.py
