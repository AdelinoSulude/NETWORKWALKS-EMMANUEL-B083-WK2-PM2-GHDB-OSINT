# NETWORKWALKS-EMMANUEL-B083-WK2-PM2-GHDB-OSINT
Week 2 Project Module 2 — GHDB &amp; OSINT
# 🧪 CyberLab — Week 2 | Module 2: GHDB & OSINT

## 🎯 Objective

Practice Google Hacking Database (GHDB) and Open-Source Intelligence (OSINT) techniques to identify publicly indexed information using search-engine operators.

---

## 📹 Task 1 — Security Camera Reconnaissance

### Objective

Use GHDB search techniques to identify publicly indexed security-camera interfaces exposed on the Internet.

### Methodology

The following GHDB search pattern was used:

```text
intitle:"webcamXP" inurl:8080
```

The search was used to identify web interfaces associated with the WebCamXP platform.

### Summary

The exercise demonstrated how search-engine operators can be used during reconnaissance to identify publicly indexed web interfaces.

The assignment required identifying 10 exposed camera links and documenting the relevant search techniques.

For privacy and security reasons, third-party camera URLs, IP addresses, credentials, and access information are not published in this repository.

### 📸 Evidence

https://github.com/AdelinoSulude/NETWORKWALKS-EMMANUEL-B083-WK2-PM2-GHDB-OSINT/blob/main/screenshots/PM2-1.jpg

> ⚠️ This exercise was performed for educational purposes. No unauthorized access, exploitation, or interaction with third-party camera systems was performed.

---

## 📚 Task 2 — Mathematics Ebooks

### Objective

Identify 10 publicly indexed listings containing downloadable mathematics ebooks in PDF format using search-engine operators.

### Search Techniques

Examples of search operators used include:

```text
filetype:pdf "Mathematics"
```

```text
intitle:"index of" "Mathematics" pdf
```

```text
site:example.com filetype:pdf "Mathematics"
```

### Search Results

| No. | Resource | Relevant Dork |
|---:|---|---|
| 1 | Skyline University — Mathematics PDF Directory | `intitle:index.of "parent directory" mathematics pdf` |
| 2 | University of New Mexico — Mathematics 2017 | `site:unm.edu filetype:pdf "Mathematics-2017"` |
| 3 | Erewhon — Mathematics Directory | `intitle:"index of" "Math" site:erewhon.superkuh.com` |
| 4 | Giakonda — Mathematics 7 | `site:education.giakonda.org.uk/Maths/ intitle:"index of" pdf` |
| 5 | Netlib — Mathematics PDF | `"ch02-16.pdf" filetype:pdf` |
| 6 | JINR — Math Encyclopedia | `"Math_V1" filetype:pdf` |
| 7 | Basic Engineering Mathematics | `"Basic Engineering Mathematics" filetype:pdf` |
| 8 | Barton — Linear Algebra | `"Linear Algebra" filetype:pdf` |
| 9 | Matagujri College — CSM Mathematics | `intitle:"index of" "parent directory" "CSM math" pdf` |
| 10 | ISSP — Mathematical Methods | `intitle:"index of" "parent directory" "Mathematical Methods" pdf` |

### Summary

A total of **10 publicly indexed mathematics PDF resources/listings** were identified using combinations of `site:`, `filetype:pdf`, `intitle:"index of"`, and exact-phrase search operators.

### 📸 Evidence

![Mathematics PDF Search](screenshots/task2-mathematics-pdf-search.png)

---

## 📊 Key Findings

| Technique | Purpose | Result |
|---|---|---|
| GHDB | Identify search patterns for exposed web interfaces | Camera-related interfaces identified |
| `filetype:pdf` | Find PDF documents | Mathematics PDF resources identified |
| `intitle:"index of"` | Identify indexed directories | Public directory listings identified |
| `site:` | Restrict searches to specific domains | Domain-specific results identified |

---

## 💡 Key Takeaways

This module provided practical experience with search-engine reconnaissance and OSINT techniques.

I learned how search operators can be combined to locate specific types of publicly indexed information and how reconnaissance findings should be handled responsibly.

---

## 🔐 Ethical Use

This project was completed as part of the **Networkwalks Cybersecurity Internship Program** for educational purposes.

Reconnaissance and OSINT activities should only be conducted against systems and information where appropriate authorization has been granted.

Sensitive information belonging to third parties should not be accessed, exploited, or unnecessarily published.

---

## 🛠️ Tools & Techniques

`Google Search` · `GHDB` · `OSINT` · `Search Operators`

---

## 👤 Author

**Adelino Sulude**

This project was completed as part of the **Networkwalks Cybersecurity Internship Program**.

All practical research, analysis, evidence collection, and documentation in this repository were performed by **Adelino Sulude**.

**Focus:** Network & Infrastructure | Cybersecurity

---

## 🙏 Training & Credits

This project was developed based on the practical exercises and training provided through the **Networkwalks Cybersecurity Internship Program**.

**Training Instructor:**  
**Waqas Karim — CCIE**

The internship provided the learning material, project requirements, and practical exercises used as the basis for this work.

---

## 📌 Module Status

**Week 2 — Project Module 2: Completed ✅**
