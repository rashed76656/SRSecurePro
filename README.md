# SR Secure Pro - Your Ultimate Browser Security Companion

<p align="center">
  <img src="logo128.png" alt="SR Secure Pro Logo" width="150"/>
</p>

<p align="center">
  **Guard your online presence with real-time insights and robust protection.**
  <br>
  A comprehensive browser extension designed to enhance your digital security.
</p>

---

## 🛡️ Features

SR Secure Pro is packed with 7 powerful security features, all accessible from an intuitive and professional dashboard:

1.  **🔒 SC Insight (SecureConnect Insight):** Get real-time security status of your current website connection, including HTTPS/HTTP status and detailed SSL certificate information (simulated for demo).
2.  **🎣 Phishing Guard:** Protect yourself from malicious phishing attempts by checking URLs against both an in-built common phishing list and a custom list you can upload.
3.  **🚫 Tracker Blocker:** Block unwanted web trackers (ads, analytics, social trackers) to enhance your privacy and speed up Browse, powered by a filtered EasyList database.
4.  **🔑 Password Strength Analyzer:** Test your password's strength before using it anywhere, with real-time feedback and improvement tips.
5.  **📜 Security Header Analyzer:** Check important HTTP security headers for the current website to identify potential vulnerabilities in its server configuration.
6.  **🌐 Basic Web Port Scanner:** Scan common ports of a target domain or IP to identify open services (simulated for demonstration due to browser limitations).
7.  **💡 Security Tips Generator:** Get quick and practical cybersecurity tips to improve your overall online safety habits.

---

## 🚀 Installation

SR Secure Pro is designed for Google Chrome and Chromium-based browsers.

### **Method 1: Install from Chrome Web Store (Recommended)**

_Coming Soon!_ We are working to publish SR Secure Pro on the Chrome Web Store for easy and secure installation.
Once available, you will find it here:

[**Install SR Secure Pro from Chrome Web Store**](https://chrome.google.com/webstore/detail/sr-secure-pro/pnblklijmglkimiglpplhagccnggcpld) *(Inactive)*

### **Method 2: Manual Installation (For Developers / Testing)**

You can manually load SR Secure Pro in your Chrome browser for development or testing purposes.

1.  **Download the Extension Files:**
    * Download the latest `.zip` archive of SR Secure Pro from our [**Releases Page**](https://github.com/rashed76656/SRSecurePro/releases).
    * Alternatively, clone this repository:
        ```bash
        git clone https://github.com/rashed76656/SRSecurePro.git
        ```
2.  **Extract the Files:** Unzip the downloaded archive to a convenient location on your computer. If you cloned, navigate to the cloned directory.
3.  **Open Chrome Extensions Page:**
    * Open Google Chrome.
    * Type `chrome://extensions` in the address bar and press Enter.
4.  **Enable Developer Mode:**
    * In the top right corner of the Extensions page, toggle on the "Developer mode" switch.
5.  **Load Unpacked:**
    * Click on the "Load unpacked" button that appears.
    * Navigate to the folder where you extracted/cloned the SR Secure Pro extension files (the folder containing `manifest.json`). Select this folder.

SR Secure Pro should now be installed and visible in your Extensions list. You can pin it to your browser toolbar for quick access!

---

## 📖 User Manual

For a detailed guide on how to use each feature of SR Secure Pro, please refer to our comprehensive User Manual:

[**Download SR Secure Pro User Manual (PDF)**](https://github.com/rashed76656/SRSecurePro/blob/main/user_manual.pdf) *(Active)*


### Download SR Secure Pro

Get the latest version from our [Releases page](https://github.com/YourUsername/YourRepo/releases).

* [SR Secure Pro v1.0.1.zip](https://github.com/rashed76656/SRSecurePro/releases/download/v1.0.1/SR_Secure_Pro_v1.0.1.zip)
* [User Manual.pdf](https://github.com/rashed76656/SRSecurePro/blob/main/user_manual.pdf)

---

## 🛠️ Development & Contribution

SR Secure Pro is an open-source project (for educational purposes). We welcome feedback and suggestions!

### **Getting Started with Development:**

1.  **Clone the Repository:** `git clone https://github.com/rashed76656/SRSecurePro.git`
2.  **Install Dependencies:** (If any, e.g., for parsing EasyList)
    ```bash
    pip install -r requirements.txt # If you use Python for parsing
    ```
3.  **Generate `easylist_domains.js`:**
    * Download the latest `easylist.txt` from [https://easylist.to/easylist/easylist.txt](https://easylist.to/easylist/easylist.txt).
    * Place `easylist.txt` in the same directory as `parse_easylist.py`.
    * Run the Python script: `python parse_easylist.py`
    * Copy the generated `easylist_domains.js` from the script's directory to `SR_Secure_Pro/data/`.
4.  **Load Unpacked Extension:** Follow the "Manual Installation" steps above.

---
## 🧪 Testing

Phising URL : [Facebook Free Gifts](https://facebook-free-gifts.zya.me).

---
## 📧 Contact

For any inquiries or support, please contact us at: rashed76656@gmail.com

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
