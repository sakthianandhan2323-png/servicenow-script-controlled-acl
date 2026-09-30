# Script-Controlled ACL – Restrict Record Access Based on Field Value

## Project Description
This project demonstrates a ServiceNow Access Control List (ACL)
that restricts record access based on a field value.

## ACL Script
```javascript
answer = (current.priority == '1');
