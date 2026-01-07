# Cross-Site Scripting (XSS)

**Severity:** Medium 🟠  
**Risk Rating:** Medium 🟠  
**Location:** Search Input Field

## Description
User input is reflected in the response without
proper sanitization.

## Impact
- Session hijacking
- Execution of malicious scripts

## Recommendation
- Implement output encoding
- Apply input sanitization
- Use Content Security Policy (CSP)
