# Security Advisory for DevDojo Voyager

## Description  
DevDojo Voyager versions 1.4.0 through 1.8.0 are vulnerable to command injection at the `/admin/compass` endpoint.  
An authenticated administrator can execute arbitrary system commands due to improper input handling.  
This vulnerability affects Voyager when running on Laravel 8+.

## Affected Versions  
✅ **Impacted:** 1.4.0 - 1.8.0 (running on Laravel 8+)  

## Recommendation  
🔹 **Disable the Compass feature (`/admin/compass`) if not required.**  
