> ⚠️ **SECURITY WARNING**  
> If this file did **not** come from the official GitHub repository:  
>  
> **https://github.com/G-Azon/GoSpam**  
>  
> STOP the installation immediately. Using modified or unofficial versions may result in system compromise, data loss, or legal consequences.

---

## 🔧 Description

GoSpam is a customizable tool developed by **Lazon** for performing high-volume HTTP request tests against target endpoints.  
This tool is primarily designed for **educational**, **experimental**, and **authorized load testing** on your own infrastructure.

---

## ⚠️ Legal Disclaimer

- This tool **must only be used for legal purposes**, such as stress testing **your own servers**, or systems for which you have **explicit written authorization**.  
- Using GoSpam against third-party systems without permission may be illegal under local or international law.  
- The creators of GoSpam (**Lazon**) are **not responsible** for any misuse or illegal activity performed with this tool.  
- By using this software, you agree to comply with all laws and regulations applicable in your jurisdiction.

---

## 📦 Dependencies

GoSpam automatically installs the following Python packages on first run:

- `colorama`  
- `aiohttp`  
- `pyfiglet`  
- `contsys`  

---

## ▶️ How to Use

Run the Python script with:

```
python gosspam.py
```

You will be prompted to:

- Enter a **target URL or IP**  
- Enter a **message** (JSON content)  
- Choose a **method** (GET, POST, PATCH, DELETE, etc.)  
- Set a **maximum number of requests**

The tool will then launch a batch of asynchronous HTTP requests.

---

## 📁 License

This software is licensed under a **Restricted Use License**.  
Personal use is free, but commercial use requires a paid license.

---

## 📌 Notes

- This tool is intended for advanced users.

---

© 2025 **Lazon** — All rights reserved.
