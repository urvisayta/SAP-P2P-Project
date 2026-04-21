# SAP-CAPSTONE-PROJECT  
Implementation of Procure-to-Pay (P2P) Cycle in SAP MM, demonstrating end-to-end procurement process with integration of inventory management and financial accounting.

---

## Project Overview  
This project explains the end-to-end Procure-to-Pay (P2P) process in SAP Materials Management (MM). The P2P cycle is a key business process in supply chain management that covers procurement of materials from vendors and payment processing.

The project demonstrates how procurement activities are integrated with inventory management and financial accounting in SAP, ensuring efficiency, transparency, and accuracy.

Note: This project is a conceptual implementation of SAP MM. Screenshots and system execution are illustrative due to limited access to a live SAP system.

---

## Problem Statement  
Organizations require an efficient system to manage procurement, vendor transactions, and payments. Manual processes often lead to:
- Delays in procurement approvals  
- Lack of visibility in inventory  
- Errors in invoice processing  
- Poor coordination between departments  

This project shows how SAP MM automates the Procure-to-Pay cycle to ensure:
- Accurate procurement tracking  
- Proper inventory management  
- Seamless financial integration  

---

## Business Scenario  
ABC Pvt Ltd is a manufacturing company that procures raw materials from external vendors to produce finished goods. The company uses SAP MM to manage procurement activities efficiently and ensure timely availability of materials.

---

## Process Flow  
Purchase Requisition → Purchase Order → Goods Receipt → Invoice Verification → Payment  

---

## Modules Used  
- SAP MM (Materials Management)  
- SAP FI (Financial Accounting)  

---

## Process Steps  

### Purchase Requisition (ME51N)  
Internal document created to request procurement of materials  

### Purchase Order (ME21N)  
Formal document issued to vendor for purchasing goods  

### Goods Receipt (MIGO)  
Goods are received and inventory is updated  

### Invoice Verification (MIRO)  
Vendor invoice is verified using 3-way matching  

### Payment (F-53 / F110)  
Payment is processed manually or automatically  

---

## Organizational Structure  
- Company Code: ABCD  
- Plant: PL01  
- Storage Location: SL01  
- Purchasing Organization: PO01  

---

## Master Data Used  
- Material Master (MM01)  
- Vendor Master (XK01)  
- Purchasing Info Record (ME11)  

---

## Accounting Entries  

Goods Receipt (MIGO):  
Inventory A/c        Dr  
   To GR/IR A/c  

Invoice Verification (MIRO):  
GR/IR A/c        Dr  
   To Vendor A/c  

Payment (F-53 / F110):  
Vendor A/c        Dr  
   To Bank A/c  

---

## Advantages  
- Automation of procurement process  
- Improved accuracy  
- Transparency in transactions  
- Better vendor management  
- Integration with financial accounting  

---

## Project Structure  
/project-report  
│  
├── SAP_P2P_Project_Report.pdf  
├── screenshots/  
├── flowchart.png  
└── README.md  

---

## Tools Used  
- SAP MM (Conceptual Implementation)  
- SAP FI Integration  
- Microsoft Word (Documentation)  
- GitHub (Version Control and Submission)  

---

## Unique Points  
- Implementation of 3-way matching (PO, GR, Invoice)  
- Integration between SAP MM and SAP FI  
- End-to-end procurement lifecycle simulation  
- Real-time accounting impact of transactions  

---

## Future Improvements  
- Integration with SAP BTP for cloud-based procurement  
- Automation in vendor selection  
- Real-time analytics dashboards  
- Advanced reporting and monitoring  

---

## Conclusion  
The Procure-to-Pay (P2P) cycle in SAP MM provides a structured and efficient approach to procurement. It integrates purchasing, inventory, and financial accounting into a single system, ensuring accuracy, transparency, and better control over business operations.

---

## Author  
Name: URVI SAYTA  
Course: B.Tech IT (6th Semester)  
College: Kalinga Institute of Industrial Technology (KIIT)
