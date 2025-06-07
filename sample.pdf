import pdfplumber

def extract_text_from_pdf(file_path):
    all_text = ""
    with pdfplumber.open(file_path) as pdf:
        for page in pdf.pages:
            text = page.extract_text()
            all_text += text if text else ''
    return all_text

if _name_ == "_main_":
    pdf_text = extract_text_from_pdf("sample.pdf")
    print(pdf_text)