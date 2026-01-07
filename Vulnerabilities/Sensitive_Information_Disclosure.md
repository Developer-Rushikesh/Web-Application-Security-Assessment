# Sensitive Information Disclosure

**Severity:** Low 🟢  
**Risk Rating:** Low 🟢  
**Location:** HTTP Response Headers

## Description
Server headers reveal technology details such
as Nginx and PHP versions.

## Impact
- System fingerprinting

## Recommendation
- Disable server version disclosure
- Configure secure HTTP headers
