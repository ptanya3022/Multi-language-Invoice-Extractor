# Multi-language-Invoice-Extractor using Gemini AI  

A powerful **AI-powered invoice extraction tool** that extracts key invoice data from images in multiple languages. This application uses **Google Gemini AI (Gemini 1.5 Flash)** to process invoice images and provide structured insights.

## 🚀 Features  
✅ Supports invoices in multiple languages  
✅ Uses **Google Gemini 1.5 Flash** for intelligent text extraction  
✅ Handles handwritten and printed invoices  
✅ Provides structured invoice details like date, total amount, tax, etc.  
✅ Simple and intuitive **Streamlit UI**  

## 📈 Business Impact  
Manually extracting invoice details is time-consuming and error-prone, especially for businesses dealing with invoices in multiple languages. This tool automates the process, helping:  

✔ **Finance & Accounting Teams** – Quickly extract key invoice details without manual data entry.  
✔ **E-commerce Platforms** – Process supplier invoices from different regions efficiently.  
✔ **Businesses with Global Clients** – Handle invoices in multiple languages without translation efforts.  
✔ **Automates Missing Data Detection** – If specific details are absent in the invoice, the model **identifies missing information**, improving accuracy.  

## 🤖 AI Integration  
- Uses **Google Gemini AI (Gemini 1.5 Flash)** to extract key invoice details like **invoice number, date, total amount, vendor name, and tax details** from images.  
- Unlike traditional OCR, it **understands structured invoice layouts** and retrieves specific details without requiring predefined templates.  
- If a requested detail is missing from the invoice, the model **intelligently responds** by stating that the information is unavailable.  

## 🎯 How It Works  
1. **Upload an invoice image** (JPG, JPEG, PNG)  
2. **Gemini AI processes** the image and extracts details  
3. **Displays structured invoice data** in a readable format  

## 🔗 Live Demo  
[![Streamlit App](https://img.shields.io/badge/Streamlit-Online-blue)](https://multi-language-invoice-extractor-k4bm5erizra3bmsem6itcx.streamlit.app/)  

## 🛠️ Tech Stack  
- **Python** 🐍  
- **Streamlit** (Web UI)  
- **Google Gemini 1.5 Flash** (AI Model)  
  
## 🖥️ Running Locally  

### Prerequisites  
- Python 3.10+ installed  
- Google Gemini API Key  

### Installation  

```bash
# Clone the repository
git clone https://github.com/ptanya3022/Multi-Language-Invoice-Extractor.git

# Navigate to the project folder
cd Multi-Language-Invoice-Extractor

# Install dependencies
pip install -r requirements.txt

# Run the Application
streamlit run app.py
