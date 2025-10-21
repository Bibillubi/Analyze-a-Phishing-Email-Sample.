# Analyze-a-Phishing-Email-Sample.
I analyzed an email header using Outlook and Google Admin Toolbox to understand message routing, SPF, DKIM, and DMARC authentication. For URL analysis, I used VirusTotal with a safe Amazon link to demonstrate how URL reputation and security scanning work without using any suspicious URLs.

---

# 🕵️‍♀️ Email Header & URL Analysis

![Status](https://img.shields.io/badge/Project-Completed-brightgreen?style=flat-square)
![Tool](https://img.shields.io/badge/Tools-Outlook%20|%20Google%20Admin%20Toolbox%20|%20VirusTotal-blue?style=flat-square)
![Category](https://img.shields.io/badge/Category-Cybersecurity-lightgrey?style=flat-square)

---

## 📧 Project Overview

This project focuses on the **analysis of an email header** using tools like [**Microsoft Outlook**](https://www.microsoft.com/en-in/microsoft-365/outlook/email-and-calendar-software-microsoft-outlook), [**Google Admin Toolbox**](https://toolbox.googleapps.com/apps/messageheader/), and [**VirusTotal**](https://www.virustotal.com/).
The main goal was to understand how to extract, inspect, and interpret email headers to detect potential spoofing or phishing indicators.

real phishing or spam email , a safe and legitimate URL (Amazon) was used for demonstration in VirusTotal to illustrate how URL scanning works securely and ethically.



Tools Used

| Tool                                                                                                                        | Purpose                                                                                 |
| --------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| 📨 [Microsoft Outlook](https://www.microsoft.com/en-in/microsoft-365/outlook/email-and-calendar-software-microsoft-outlook) | To obtain and view the raw **email header**                                             |
| 🧠 [Google Admin Toolbox (Messageheader Tool)](https://toolbox.googleapps.com/apps/messageheader/)                          | To analyze and interpret header details like SPF/DKIM results and routing paths         |
| 🛡️ [VirusTotal](https://www.virustotal.com/)                                                                               | To demonstrate **URL reputation analysis** using a safe link (`https://www.amazon.com`) |

Methodology

1] Header Extraction (Outlook)

* Opened an email in **Outlook**.
* Used **“View Message Source”** or **“View Headers”** to extract the complete header.
* Copied and saved it for analysis.

2] Header Analysis (Google Admin Toolbox)

* Pasted the header into **Google Admin Toolbox → Messageheader Analyzer**.
* Observed details such as:

  * **Routing path and hops**
  * **SPF, DKIM, and DMARC authentication**
  * **Message delay time**

3] URL Demonstration (VirusTotal)

* Used a safe URL: `https://www.amazon.com`.
* Uploaded it to **VirusTotal** to demonstrate URL scanning.
* The report showed **clean and safe results**, confirming legitimate behavior of a trusted website.

---

⚙️ Findings

* Understood how **email routing and authentication** appear in headers.
* Verified **SPF/DKIM** status using the Admin Toolbox.
* VirusTotal demo confirmed that **safe URLs** are detected as clean and trusted.

Key Learnings

✅ Email headers reveal important forensic details for identifying spoofing.
✅ Google Admin Toolbox simplifies complex header analysis.
✅ VirusTotal is a reliable platform for URL scanning, even for demonstration using safe links.


📂 Project Structure

```
📁 Email-Header-Analysis/
 ├── header_analysis_report.pdf
 ├── url_virustotal_demo.pdf
 ├── sample_email_header.txt
 ├── README.md
```
Conclusion

This project demonstrates the process of performing **email header analysis** and **safe URL verification** using trusted cybersecurity tools. Even with a legitimate link, the workflow effectively showcases real-world techniques used to detect phishing or spoofed messages.

Author

Vistruti Mahajan

Cybersecurity Enthusiast | Email Security Learner
📫 Connect: [LinkedIn](www.linkedin.com/in/mahajan-vistruti-98417a344) | [VirusTotal](https://www.virustotal.com) | [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/)





