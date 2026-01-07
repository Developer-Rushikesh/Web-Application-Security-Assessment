# SQL Injection

**Severity:** Critical 🔴  
**Risk Rating:** High 🔴  
**Location:** /listproducts.php?cat=

## Description
Improper input validation allows SQL queries
to be manipulated by the user.

## Impact
- Unauthorized database access
- Data leakage

## Recommendation
- Use prepared statements
- Implement proper input validation
- Disable detailed SQL error messages
