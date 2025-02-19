# 📧 UiPath Automated Newsletter Distribution  

This **UiPath automation** streamlines the process of sending newsletters via **Gmail**, triggered by a new **Excel file** in **Google Drive**. The bot verifies recipient details, personalizes messages, and ensures smooth execution with error handling.

## 🚀 Features  

✔ **Event-Triggered Execution:** Listening for the creation of `UsersNewsletter.xlsx` in Google Drive.  
✔ **Google Drive API Integration:** Finding the Excel file,Downloading it to a local folder
✔ **Using recipient details:** reading the Excel file to a data table, and iterating over each row to use recipient details 
✔ **Dynamic Email Personalization:** Extracts recipient info and sends customized emails with a **PDF attachment**.  
✔ **Exception Handling & Logging:** Implements **Try-Catch, Throw, and Rethrow** with info/warn logs.  

## 🔧 Setup Instructions  

1️⃣ **Prerequisites:**  
   - UiPath Studio installed  
   - Google Drive & Gmail integrations configured in **UiPath Integration Service**  
   - A valid **Gmail account** for sending emails  

2️⃣ **Execution Steps:**  
   - The bot **polls Google Drive every minute** to detect the `UsersNewsletter.xlsx` file.  
   - If found, it downloads and reads the file into a **Data Table**.  
   - For each row, it checks if the newsletter should be sent.  
   - If **"Yes"**, the bot sends a **personalized email** with the attached **PDF newsletter**.  

## 🛠 Technologies Used  

- **UiPath Studio & Assistant**  
- **UiPath Integration Service (Google Drive & Gmail)**  
- **Excel Processing & Data Tables**  
- **Logging & Exception Handling**  

## 📌 Repository  

🔗 **GitHub Link:** [[Repository URL]](https://github.com/imad-pro/GDrive-Integration.git) 

---
💡 **Feel free to contribute or share your thoughts!**
