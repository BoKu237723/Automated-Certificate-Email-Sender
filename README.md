# Automated-Certificate-Email-Sender (Version-1.0.1)

```

                            ______    ______   ________   ______  
                           /      \  /      \ /        | /      \ 
                          /$$$$$$  |/$$$$$$  |$$$$$$$$/ /$$$$$$  |
                          $$ |__$$ |$$ |  $$/ $$ |__    $$ \__$$/ 
                          $$    $$ |$$ |      $$    |   $$      \ 
                          $$$$$$$$ |$$ |   __ $$$$$/     $$$$$$  |
                          $$ |  $$ |$$ \__/  |$$ |_____ /  \__$$ |
                          $$ |  $$ |$$    $$/ $$       |$$    $$/ 
                          $$/   $$/  $$$$$$/  $$$$$$$$/  $$$$$$/  
                                        
```

## Description

A python tool to automate sending personalized certificates pngs (or other files) to multiple recipients via SMTP. Used json file format. 

## 🚀 Features

Bulk Email Sending:  
- **Send certificates to multiple recipients from a JSON file** 

Secure SMTP Connection:  
- **Uses Gmail's SMTP server with TLS encryption** 

Automatic Attachment Handling:  
- **Attaches PNG certificate files automatically** 

Error Handling:  
- **Robust error checking for missing files and invalid data** 

Progress Tracking:  
- **Real-time status updates and summary report** 

Customizable Content:  
- **Easy to modify email subject and body text** 

---

🚀 *This Version-1 is a major step to improve the current code and to implement major updates in the future!*

---

## ⚠️ Requirements

- Python 3.6+
- Gmail account with 2FA enabled
- App Password


### 📁 Required Files Structure
```
project_folder/
├── email_sender.py          # This script
├── emails.json              # Recipient data (email & PNG filenames)
└── certificates/            # Folder containing PNG certificates
    ├── certificate1.png
    ├── certificate2.png
    └── ...
```
---

## 💌 Possible Next Features Updates
These following are ideas for features that could be added in future versions.

### Enhanced Training Data & MongoDB Integration
- Multiple Template support
- CSV Support
- Saved History
