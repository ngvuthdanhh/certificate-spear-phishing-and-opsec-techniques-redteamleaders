# 07. Evasion Techniques

Security systems continuously improve; evasion techniques must adapt.

## 📤 Email Evasion
- Avoiding spam filters  
- Maintaining clean sending reputation  
- Using domain alignment (SPF, DKIM, DMARC)  

## 🧪 Attachment Evasion
- Avoid macros unless strictly necessary  
- Use benign document templates  
- Ensure clean metadata  
- Avoid obvious indicators (obfuscation noise, encrypted zips)  

## 📡 Infrastructure Evasion
- Avoid hosting phishing content on known bad IPs  
- Remove fingerprints (headers, TLS fingerprints, favicon, server banners)  
- Avoid C2-like patterns  

The goal is to appear indistinguishable from legitimate business email traffic.
