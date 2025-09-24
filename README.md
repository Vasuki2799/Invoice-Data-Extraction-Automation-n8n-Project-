# Invoice Data Extraction & Automation (n8n Project)

This project demonstrates how to **automate invoice data extraction** using **n8n**.  
A sample invoice PDF is processed via the **OCR API**, and key details are automatically logged into **Google Sheets**.

---

## 🔹 Project Workflow
**Workflow Nodes Used:**
1. **Manual Trigger** – starts the workflow manually for testing.  
2. **HTTP Request** – sends the sample invoice PDF URL to OCR API (`https://api.ocr.space/parse/image`).  
3. **Code (JavaScript)** – extracts key fields (Date, Vendor, Amount) from the OCR response.  
4. **Google Sheets (Append Row)** – stores the extracted details in a sheet.  

---

## 🔹 Features
- Automated invoice processing (no manual data entry)  
- Extracts **Date, Vendor, and Amount** from invoice PDFs  
- Logs data into **Google Sheets** in real-time  
- Reduces manual work by ~60%  

---

## 🔹 Tools & Technologies
- **n8n** (Workflow Automation)  
- **OCR API (ocr.space)**  
- **Google Sheets API**  

---

## 🔹 Screenshots
📷 Workflow in n8n:  
![Workflow Screenshot]<img width="1440" height="852" alt="Workflow" src="https://github.com/user-attachments/assets/5be75f13-b061-4ad8-a091-7436c76aadba" />


📷 Extracted Data in Google Sheets:  
![Google Sheets Result]<img width="1440" height="852" alt="Rename" src="https://github.com/user-attachments/assets/da6aaf2d-46c4-4bcb-b5d8-dd87dbaeeffd" />
 

---

## 🔹 Future Enhancements
- Replace manual trigger with **Google Drive Trigger** for real uploaded invoices.  
- Add error-handling for failed OCR reads.  
- Extend workflow to send notifications in Slack/Teams.  

---

## 🔹 Author
**Vasuki A**  
- LinkedIn: https://www.linkedin.com/in/vasuki27/  
- GitHub: github.com/Vasuki2799 
