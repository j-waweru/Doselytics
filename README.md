
# 🧠 Doselytics – AI-Powered Supplement Analyzer

Doselytics is an AI-driven tool that analyzes supplement label images to evaluate the **effectiveness**, **accuracy**, and **safety** of nutritional products.  
Built using `Gradio`, `Gemini API`, and OCR (Tesseract), Doselytics aims to help users make informed choices about supplements.

---


## 🔍 Why I built the app 🦾🧖‍ 👩‍🎓   

- 👩‍🎓 I built the app for my 4'th year Project as part of my course requirements.   
- 🧖‍ I chose this app because; 
- 📊 I had seen far too many inneffective supplements(underdosed,poorly researched) being sold.  
- 🦾 So I decide to leverage the power of AI to create an app that would analyze supplement labels for scientific accuracy  
      and empower users to make better choices when buying supplements.  

---



## 📦 Features

- 🧾 Upload supplement label images for analysis  
- 🔍 Extracts ingredients, quantities, and units with OCR  
- 📊 Evaluates dosage accuracy and effectiveness using LLM  
- 🧠 Detects marketing tricks (e.g., proprietary blends)  
- ⭐ Provides AI-powered supplement ratings (1–10)  
- 📝 Downloadable Markdown report  
- 🖼️ Clean, responsive Gradio user interface  
- 💬 FAQ section for user guidance

---

## 🚀 How It Works

1. **Upload an image** of a supplement nutrition label.
2. The app uses **OCR** to extract text and corrects common errors.
3. The extracted data is sent to **Gemini 1.5 Flash** to identify ingredients and dosages.
4. The system matches ingredients against a **database**.
5. It returns:
   - Ingredient usage and research
   - Dosage evaluation
   - Red flags or marketing tricks
   - An overall rating

---


## 🛠️ Tech Stack

- Python
- [Gradio](https://www.gradio.app/)
- [Gemini 1.5 Flash (Google AI)](https://ai.google.dev/)
- Tesseract OCR (`pytesseract`)
- Supplement database
- Google Colab (development)

---

## 📁 Project Structure

```

├── finaldoselytics_py.ipynb                  # Main Gradio app
├── ingdb.docx    # Local supplement DB
├── req.txt  #Additional requirements to be installed.  
├── images                 # Images and UI banners
├── README.md

````

---

## 💾 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/j-waweru/Doselytics.git
cd Doselytics

# Install requirements
The app was developed and run in google colab which already provides most of the libraries.  
Additional requirements are included in the req.txt

# Run the app
python finaldoselytics_py.ipynb
````

*Preferred*  
*Use in Google Colab for free hosting.*  

---

## 📚 FAQs

See the **FAQ tab** in the app for common questions on accuracy, OCR, and proprietary blends.

---

## 🧪 Future Improvements

* Improve on the database
* Better User interface
* Better proprietary blend analysis

---

## 🙏 Acknowledgments

* [Gemini API by Google](https://ai.google.dev/)
* [Gradio UI](https://gradio.app/)
* [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
* [Examine.com](https://examine.com/) for supplement research references

---
