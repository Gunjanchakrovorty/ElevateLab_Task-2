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


### 🔎 Initial Red Flags
- ❌ Fake domain mimicking Amazon
- ❗ Urgent, emotionally triggering language
- ⚠️ Dangerous phishing link pretending to be a login page

---

## 🔍 Technical Analysis of Phishing Indicators

| 🔢 | **Indicator**                | **Description** |
|-----|-----------------------------|------------------|
| 1️⃣ | **Spoofed Sender**          | `support@amaz0n-security.com` appears legit but is a typo-squatted domain |
| 2️⃣ | **Phishing Link**           | Hidden behind a legitimate-looking text; goes to `amaz0n-secure-login.com` |
| 3️⃣ | **Urgency/Threat**          | Creates pressure to act fast: "account will be suspended in 24 hrs" |
| 4️⃣ | **Language Tricks**         | Fear-based social engineering tactics |
| 5️⃣ | **Header Issues**           | SPF check failed, no DKIM present |
| 6️⃣ | **Visual Deception**        | Uses Amazon branding in content to seem trustworthy |
| 7️⃣ | **Hover Link Mismatch**     | Hovering shows a different link than the anchor text |
| 8️⃣ | **Grammar/Style Flaws**     | Awkward phrasing and lack of branding consistency |

---

## 🧪 Email Header Analysis (MXToolbox)

- ✅ **Tool Used**: [https://mxtoolbox.com/EmailHeaders.aspx](https://mxtoolbox.com/EmailHeaders.aspx)
- 🔍 **SPF**: Failed – sender not authorized to send on behalf of domain
- 🔍 **DKIM**: Absent – email lacks proper signature verification
- 🔍 **Return-Path**: Did not match "From" address
- 🌍 **Origin IP**: Traced to an unusual/untrusted country

---

## 🧠 Social Engineering Breakdown

| Technique        | Used? | Explanation |
|------------------|-------|-------------|
| Authority        | ✅     | Pretends to be Amazon support |
| Urgency          | ✅     | “Verify in 24 hours or lose access” |
| Fear             | ✅     | Threatens with account deactivation |
| Familiarity      | ✅     | Uses Amazon branding and language |
| Scarcity         | ❌     | Not used in this example |

---

## 🧰 Tools Used

| Tool | Purpose |
|------|---------|
| MXToolbox | Header analysis |
| VirusTotal | Link and attachment scanning |
| Whois Lookup | Domain registration info |
| Email Client | To view headers and links |
| Browser Inspector | To view URL redirect behavior |

---

## 🖼️ Screenshots

| Image | Description |
|-------|-------------|
| ![Email Sample](images/phishing-email-sample.png) | Screenshot of the phishing email |
| ![Hover Link](images/link-hover-proof.png) | Proof of mismatched URLs |
| ![Header Analysis](images/email-header-analysis.png) | Header results showing SPF fail & DKIM missing |

> Upload the above images in a folder named `/images`.

---

## 📂 Folder Structure

