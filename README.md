# Security Advisory for DevDojo Voyager

## Description  
DevDojo Voyager versions 1.4.0 through 1.8.0 are vulnerable to command injection at the `/admin/compass` endpoint.  
An authenticated administrator can execute arbitrary system commands due to improper input handling.  

## Affected Versions  
✅ **Impacted:** 1.4.0 - 1.8.0 (running on Laravel 8 and later)  

## Recommendation  
🔹 **Disable the Compass feature (`/admin/compass`) if not required.**  
## POC
![voyager-rce-poc](https://github.com/user-attachments/assets/e2498ac8-19cd-492d-bc2b-e0051c5cd083)


