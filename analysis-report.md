# Phishing Email Analysis Report

**Sample Email:** `sample-email.txt`  
**Date Analyzed:** 2025-08-05  

---

### 1. Sender Analysis
- **Sender Email:** `support@paypa1.com`
- **Suspicious Trait:** Domain spoofing (1 instead of l in "paypal")

### 2. Header Check
- **Result:** SPF and DKIM failed (indicating spoofed source)
- **Source IP:** Originated from a free hosting server, not PayPal.

### 3. Suspicious Links / Attachments
- **Link Displayed:** `PayPal Verify`
- **Real Link:** `http://malicious-verify-account.ru/login`
- **Attachment:** `Account_Verification.zip` (potential malware)

### 4. Language and Tone
- Urgent and threatening language:  
  *"Your account will be suspended in 24 hours!"*

### 5. Spelling & Grammar
- Minor errors like “PaypaI” instead of “PayPal”.

### 6. Summary of Phishing Traits
- Spoofed sender address
- Failed SPF/DKIM authentication
- Suspicious external link
- Malware attachment
- Urgent tone

---

**Conclusion:**  
This is a **classic phishing attempt** targeting PayPal users to steal credentials.
