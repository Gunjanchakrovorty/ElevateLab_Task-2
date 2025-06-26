# 🛡️ Phishing Email Analysis Report

## 🚀 Cyber Security Internship – Task 2

This repository documents the phishing email analysis task performed as part of the Cyber Security Internship. The objective was to investigate a suspicious email and identify phishing techniques using manual inspection and email header analysis.

---

## 🎯 Objective

Analyze a phishing email for malicious signs like email spoofing, suspicious links, mismatched headers, and social engineering. The task is designed to improve your ability to detect threats in real-world scenarios and strengthen email security awareness.

---

## 📚 Key Concepts

- **Phishing**: Fraudulent attempt to obtain sensitive information via disguised emails.
- **Email Spoofing**: Forging the sender’s address to appear legitimate.
- **Email Headers**: Metadata that can reveal the true origin of the email.
- **Social Engineering**: Psychological manipulation to trick victims into providing sensitive data.
- **SPF/DKIM/DMARC**: Email authentication protocols that verify sender legitimacy.

---

## 📝 Task Summary

- **Task Title:** Analyze a Phishing Email
- **Internship Module:** Threat Detection and Email Forensics
- **Tools Used:** MXToolbox, Email Client, VirusTotal, Whois Lookup
- **Deliverable:** A detailed analysis report with screenshots

---

## 📨 Sample Phishing Email (Analyzed)


---

## 🔍 Phishing Indicators Identified

| No. | Indicator                | Description |
|-----|--------------------------|-------------|
| 1️⃣ | Spoofed Email Address    | `amaz0n-security.com` resembles `amazon.com` |
| 2️⃣ | Suspicious Link          | Links to malicious domain not related to Amazon |
| 3️⃣ | Urgent Tone              | Threats like “24-hour suspension” |
| 4️⃣ | Threat Language          | “Failure to comply…” used to scare |
| 5️⃣ | Grammar Errors           | Awkward and robotic wording |
| 6️⃣ | Hover Link Mismatch      | Shown URL ≠ actual redirect |
| 7️⃣ | Header Discrepancies     | SPF fail, DKIM missing |
| 8️⃣ | Social Engineering       | Pretends to be trusted brand (Amazon) |

---

## 🧪 Email Header Analysis

- 🔍 **SPF**: ❌ Fail — not authorized sender  
- 🔍 **DKIM**: ❌ Absent — no digital signature  
- 🔍 **Return-Path**: Mismatched from sender  
- 🌍 **Origin IP**: Traced to suspicious country  
- ✅ **Tool Used**: [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx)

---

## 🖼️ Screenshots

### 1. 📧 Phishing Email Sample
![Phishing Email Sample](https://security.virginia.edu/sites/security/files/styles/scale_600/public/phish%20image_0.png?itok=rVkQtFHV)

### 2. 🔗 Hover Link Mismatch
![Hover Link Proof](https://www.computersplusrepair.com/wp-content/uploads/2017/01/Amazon-Customers-Tricked-with-Ticket-Verification-Number-Phishing-Email-473445-2.jpg).

### 3. 📥 Email Header Analysis via MXToolbox
![MXToolbox Header Result](https://mxtoolbox.com/public/content/emailheaders/aol_2.jpg).

> 📌 These images were sourced for demonstration purposes. Replace them with your own for original reports.

---

## 🛠 Tools Used

| Tool         | Function                        |
|--------------|----------------------------------|
| MXToolbox    | Header inspection & SPF check   |
| VirusTotal   | URL/Attachment scanning         |
| Whois Lookup | Domain origin and validity      |
| Browser      | Link redirection checking       |
| Email Client | Raw email inspection            |

---

## 🧠 Social Engineering Breakdown

| Technique     | Used | Description |
|---------------|------|-------------|
| Authority     | ✅    | Pretends to be Amazon |
| Urgency       | ✅    | “Act now or lose access” |
| Fear          | ✅    | Account suspension threat |
| Familiarity   | ✅    | Uses Amazon logo/language |
| Scarcity      | ❌    | Not applicable in this case |

---

## 💬 Interview Questions and Answers

### 1. **What is phishing?**
Phishing is a type of cyberattack where attackers impersonate trusted entities to steal sensitive data like passwords, credit card details, or login credentials.

### 2. **What are signs of a phishing email?**
- Spoofed sender
- Suspicious or shortened URLs
- Urgent language
- Poor grammar
- Attachments asking for credentials

### 3. **What is email spoofing?**
It’s when the attacker forges the “From” address to make it look like it came from a trusted source.

### 4. **What actions to take on suspected phishing?**
- Don’t click any links
- Report to IT/security team
- Mark as spam/phishing
- Block sender if needed

---

## 🔒 How to Protect Yourself

- Always verify sender addresses
- Hover over links before clicking
- Never share credentials via email
- Use strong spam filters and antivirus
- Enable two-factor authentication (2FA)
- Educate yourself & others regularly

---

