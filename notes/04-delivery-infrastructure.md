# 04. Delivery Infrastructure

Your infrastructure determines whether emails reach inboxes safely and undetected.

## 🌐 Domains & DNS
### You must prepare:
- Clean domain (no blacklist history)  
- Proper SPF, DKIM, DMARC  
- Matching MX records  
- Neutral domain age if possible  

## 📡 SMTP Configuration
Important factors:
- IP reputation  
- TLS version  
- Reverse DNS (PTR)  
- Volume limits to avoid spam triggers  

## 🔐 OPSEC Considerations
- Isolated email infrastructure separate from primary operations  
- Use redirectors for tracking or payload hosting  
- Avoid hosting all components on the same server  
