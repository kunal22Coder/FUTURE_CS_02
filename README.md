# Phishing Email Detection & Awareness System

## Task Information

**Future Interns – Cyber Security Task 2 (2026)**

---

## Objective

The objective of this project is to analyze email samples, identify phishing indicators, classify email risk levels, and create awareness guidelines to help users recognize and avoid phishing attacks.

---

## Tools Used

* Google Message Header Analyzer
* MXToolbox Header Analyzer
* Gmail
* Microsoft Word

---

## Email Samples Analyzed

### Sample 1 – Legitimate Email

**Subject:** Apply For Summer Internship and Placement Mentorship Program

**Classification:** SAFE

**Reason:** Valid sender domain, SPF/DKIM/DMARC authentication passed, and no phishing indicators identified.

---

### Sample 2 – Payment Reminder Email

**Subject:** Payment Reminder

**Classification:** SUSPICIOUS

**Reason:** Encrypted attachment warning, missing DMARC record, and financial-related content requiring caution.

---

### Sample 3 – Phishing Email Sample

**Subject:** Phishing Email Sample

**Classification:** PHISHING

**Reason:** Presence of phishing indicators such as suspicious content, deceptive intent, and potential credential harvesting behavior.

---

## Methodology

1. Collected email samples for analysis.
2. Extracted and analyzed email headers.
3. Verified SPF, DKIM, and DMARC authentication records.
4. Examined sender information, attachments, and email content.
5. Identified phishing indicators and risk factors.
6. Classified emails as Safe, Suspicious, or Phishing.
7. Documented findings and awareness recommendations.

---

## Repository Structure

```text
FUTURE_CS_02
│
├── phishing-samples/
├── screenshots/
├── report/
└── README.md
```

---

## Key Learning Outcomes

* Understanding phishing attack techniques.
* Email header analysis using industry-standard tools.
* SPF, DKIM, and DMARC verification.
* Email risk assessment and classification.
* Security awareness and phishing prevention practices.

---

## Author

**Kunal Baviskar**
MCA Student
SVKM's Institute of Technology, Dhule

**GitHub:** https://github.com/kunal22Coder
