✅ README.md for PDF Extraction Project

# PDF Extraction Project

This Python project extracts text content from PDF files using the pdfplumber library. It is designed for standard (non-scanned) PDFs that contain machine-readable text.

---

## 📂 Project Structure

PDF_EXTRACTION_PROJECT/
├── main.py             # Main script to extract text from PDF
├── sample.pdf          # Sample input PDF file
├── requirements.txt    # List of required Python packages
├── README.md           # Project documentation

---

## 📌 Features

- Extracts text from each page of a PDF
- Outputs clean, readable text to the console
- Uses pdfplumber (not OCR) for better accuracy with text-based PDFs

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Evans44/PDF_EXTRACTION_PROJECT.git
cd PDF_EXTRACTION_PROJECT

2. Install Dependencies

pip install -r requirements.txt

3. Run the Script

python main.py

You should see the extracted text from sample.pdf printed in your terminal.

🛠 Dependencies

	•	pdfplumber
	•	PyPDF2

Install them via:

pip install pdfplumber PyPDF2

📄 Sample PDF

The file sample.pdf is used as a demo input. Replace it with your own text-based PDF files to test other documents.

📬 Contact

For questions or collaboration, feel free to reach out via GitHub or open an issue.