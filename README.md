

Project Title: AI Chemist – Streamlit Web App for Image-Based Medicine Recognition

Technologies Used: Google Gemini API, Streamlit, Python, python-dotenv

Objective:
To develop an interactive web application that allows users to recognize medicine names from images using Google’s Gemini AI model, with a secure backend configuration via dotenv for handling API keys and environment variables.
Project Overview:
AI Chemist is a Streamlit-based web application that helps users identify medicines by uploading an image of tablets, strips, or handwritten prescriptions. The app uses Gemini's multimodal capabilities to extract text or features from the image and match them with known medicine names.


Key Features:
Image Upload via Streamlit UI: Users can upload clear images of medicine packaging or tablets.
Gemini-Powered Recognition: The image is analyzed using Google’s Gemini API to extract any visible medicine name or label using OCR and vision capabilities.
Secure API Handling with dotenv: Sensitive keys such as Gemini API keys are stored securely using .env files and accessed through the python-dotenv package.
Drug Information Display: After recognition, the app fetches additional details (uses, side effects, dosage) from a backend API or database.
Responsive and Clean UI: Powered by Streamlit, with interactive feedback, progress spinners, and expandable result panels.


Workflow: 
Image Upload via Web UI
Image Preprocessing (resizing, filtering)
Gemini API call for vision analysis (via secured API key)
Text extraction or label detection
Match detected name with database
Display result and medicine details


Tech Stack:
Frontend & UI: Streamlit
Backend Integration: Gemini API (image-to-text)
Environment Config: python-dotenv for managing API keys securely


Use Cases:
Identifying unknown medicine strips/tablets
Assisting elderly or visually impaired users
Supporting health workers in remote or urgent situations

