#  Credit Card Statement Parser (HDFC Bank)

Hello there 

This repository contains a simple yet practical **PDF parser** built in Python to extract useful information from **HDFC Bank credit card statements**.

It’s part of an assignment where the goal was to:
- Parse real-world PDF bank statements  
- Extract **5 important data points**
- Demonstrate the logic clearly — that’s why it’s all inside a Jupyter Notebook

---

## What This Parser Does

From a given HDFC PDF statement, it automatically extracts:

| Field                 | Example Output           |
|-----------------------|--------------------------|
| Cardholder Name       | ADAM ANSARI              |
| Card Number           | 5268 73XX XXXX 0005      |
| Statement Date        | 14/10/2025               |
| Payment Due Date      | 03/11/2025               |
| Total Amount Due      | 8,501.00                 |

Feel free to try it on your own statement (uploaded securely via Colab).

---

## Tech & Tools

- `Python 3.x`
- [`pdfminer.six`](https://pypi.org/project/pdfminer.six/) – for PDF text extraction
- Regular Expressions – to fetch key data from weirdly formatted lines in PDFs
- Jupyter Notebook (Google Colab-friendly)

---

## Try It Yourself

You can run this notebook in Google Colab — just upload your PDF when prompted and watch the magic happen   


---

## File Included

- `credit_card_parser.ipynb`: The main notebook that:
  - Installs dependencies
  - Lets you upload a PDF
  - Extracts text
  - Parses and prints structured output (as JSON)

---

##  What I Learned (and You Can Too!)

- How to extract unstructured text from PDFs
- Crafting reliable regex patterns for real-world messy documents
- Making modular code inside a notebook 
- Keeping parsing logic flexible for future expansion

---

##  Next Steps (Roadmap)

-  HDFC support (done!)
- Add other issuers (ICICI, SBI, Axis, etc.)
- Parse list of transactions (date, merchant, amount)
- Turn into a small Flask API (upload PDF → get JSON)

---

##  Thanks for Visiting

Got ideas or feedback on making this parser smarter / cleaner / scalable?  
I'd love to hear them — feel free to open an issue or drop me a message 

