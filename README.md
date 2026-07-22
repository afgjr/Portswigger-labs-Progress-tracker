# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-54-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--22-yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-20%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 20 of 61
- **Practitioner**: 34 of 174
- **Expert**: 0 of 39

## Categories Covered

- **Authentication vulnerabilities**: 12/14 lab
- **SQL injection**: 5/18 lab
- **Access control**: 13/13 lab
- **Path traversal**: 6/6 lab
- **Command injection**: 5/5 lab
- **File upload vulnerabilities**: 6/7 lab
- **OAuth 2.0 authentication vulnerabilities**: 5/6 lab
- **Race conditions**: 2/6 lab
## Notes
- **Full Writeups**: Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
- **Tools Used**: Burp Suite

## How to Read
- **Columns**: 
  - `No`: Sequential lab number.
  - `Date`: When I solved it (YYYY-MM-DD).
  - `Topic`: Vulnerability category (e.g., API Testing, XSS).
  - `Lab Title`: Exact name from PortSwigger.
  - `Difficulty`: Apprentice, Practitioner, or Expert.
  - `Writeup Link`: Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date       | Topic          | Lab Title                                   | Difficulty  | Writeup Link |
|----|------------|----------------|---------------------------------------------|-------------|--------------|
| 1  | 2026-06-18 |SQL injection     | SQL injection vulnerability in WHERE clause allowing retrieval of hidden data  |APPRENTICE | N/A |
| 2  | 2026-06-18 |SQL injection     |  SQL injection vulnerability allowing login bypass |APPRENTICE   | N/A |
| 3  | 2026-06-19 |SQL injection     |  SQL injection UNION attack, determining the number of columns returned by the query |PRACTITIONER   | N/A |
| 4  | 2026-06-19 |SQL injection     |   SQL injection UNION attack, finding a column containing text |PRACTITIONER   | N/A |
| 5  | 2026-06-19 |SQL injection     |  SQL injection UNION attack, retrieving data from other tables |PRACTITIONER   | N/A |
| 6  | 2026-06-23 |Authentication vulnerabilities     |  Username enumeration via different responses |APPRENTICE   | N/A |
| 7  | 2026-06-25 |Authentication vulnerabilities     |  Username enumeration via subtly different responses |PRACTITIONER   | N/A |
| 8  | 2026-06-25 |Authentication vulnerabilities     |  Username enumeration via response timing |PRACTITIONER   | N/A |
| 9  | 2026-06-25 |Authentication vulnerabilities     |  Broken brute-force protection, IP block |PRACTITIONER   | N/A |
| 10 | 2026-06-25 |Authentication vulnerabilities     |  Username enumeration via account lock|PRACTITIONER   | N/A |
| 11 | 2026-06-27 |Authentication vulnerabilities     |  2FA simple bypass|APPRENTICE   | N/A |
| 12 | 2026-06-27 |Authentication vulnerabilities     |  2FA broken logic|PRACTITIONER   | N/A |
| 13 | 2026-06-27 |Authentication vulnerabilities     |  Brute-forcing a stay-logged-in cookie|PRACTITIONER   | N/A |
| 14 | 2026-07-03 |Path traversal  |  File path traversal, simple case|APPRENTICE   | N/A |
| 15 | 2026-07-03 |Path traversal  | File path traversal, traversal sequences blocked with absolute path bypass|PRACTITIONER   | N/A |
| 16 | 2026-07-03 |Path traversal  |  File path traversal, traversal sequences stripped non-recursively|PRACTITIONER   | N/A |
| 17 | 2026-07-03 |Path traversal  | File path traversal, traversal sequences stripped with superfluous URL-decode   |PRACTITIONER | N/A |
| 18 | 2026-07-03 |Path traversal  |  File path traversal, validation of start of path|PRACTITIONER   | N/A |
| 19 | 2026-07-03 |Path traversal  |  File path traversal, validation of file extension with null byte bypass|PRACTITIONER   | N/A |
| 20 | 2026-07-04 |Command injection  |  OS command injection, simple case|APPRENTICE   | N/A |
| 21 | 2026-07-04 |Command injection  |  Blind OS command injection with time delays|PRACTITIONER   | N/A |
| 22 | 2026-07-04 |Command injection  |  Blind OS command injection with output redirection|PRACTITIONER   | N/A |
| 23 | 2026-07-04 |Command injection  |  Blind OS command injection with out-of-band interaction|PRACTITIONER   | N/A |
| 24 | 2026-07-04 |Command injection  |  Blind OS command injection with out-of-band data exfiltration|PRACTITIONER   | N/A |
| 25 | 2026-07-08 |Access control  |  Unprotected admin functionality|APPRENTICE   | N/A |
| 26 | 2026-07-08 |Access control  |  Unprotected admin functionality with unpredictable URL|APPRENTICE   | N/A |
| 27 | 2026-07-08 |Access control  |  User role controlled by request parameter|APPRENTICE   | N/A |
| 28 | 2026-07-08 |Access control  |  User role can be modified in user profile|APPRENTICE   | N/A |
| 29 | 2026-07-09 |Access control  |  URL-based access control can be circumvented|PRACTITIONER   | N/A |
| 30 | 2026-07-09 |Access control  |  User ID controlled by request parameter|APPRENTICE   | N/A |
| 31 | 2026-07-09 |Access control  |  User ID controlled by request parameter, with unpredictable user IDs|APPRENTICE   | N/A |
| 32 | 2026-07-09 |Access control  |  User ID controlled by request parameter with data leakage in redirect|APPRENTICE   | N/A |
| 33 | 2026-07-10 |Access control  |  User ID controlled by request parameter with password disclosure|APPRENTICE   | N/A |
| 34 | 2026-07-10 |Access control  |  Insecure direct object references|APPRENTICE   | N/A |
| 35 | 2026-07-11 |Access control  |   Method-based access control can be circumvented|PRACTITIONER   | N/A |
| 36 | 2026-07-11 |Access control  |  Multi-step process with no access control on one step|PRACTITIONER   | N/A |
| 37 | 2026-07-11 |Access control  |  Referer-based access control|PRACTITIONER   | N/A |
| 38 | 2026-07-15 |File upload vulnerabilities  |  Remote code execution via web shell upload|APPRENTICE   | N/A |
| 39 | 2026-07-15 |File upload vulnerabilities  |  Web shell upload via Content-Type restriction bypass|APPRENTICE   | N/A |
| 40 | 2026-07-15 |File upload vulnerabilities  |  Web shell upload via path traversal|PRACTITIONER   | N/A |
| 41 | 2026-07-16 |File upload vulnerabilities  |   web shell upload via extension blacklist bypass|PRACTITIONER   | N/A |
| 42 | 2026-07-16 |File upload vulnerabilities  |  Web shell upload via obfuscated file extension|PRACTITIONER   | N/A |
| 43 | 2026-07-17 |File upload vulnerabilities  |  Remote code execution via polyglot web shell upload|PRACTITIONER   | N/A |
| 44 | 2026-07-17 |Authentication vulnerabilities  |  Offline password cracking|PRACTITIONER   | N/A |
| 45 | 2026-07-17 |Authentication vulnerabilities  |  Password reset broken logic|APPRENTICE   | N/A |
| 46 | 2026-07-18 |Authentication vulnerabilities  |  Password reset poisoning via middleware|PRACTITIONER   | N/A |
| 47 | 2026-07-18 |Authentication vulnerabilities  |  Password brute-force via password change|PRACTITIONER   | N/A |
| 48 | 2026-07-18 |OAuth 2.0 authentication vulnerabilities  |  Authentication bypass via OAuth implicit flow|APPRENTICE   | N/A |
| 49 | 2026-07-20 |OAuth 2.0 authentication vulnerabilities  |  Forced OAuth profile linking|PRACTITIONER   | N/A |
| 50 | 2026-07-20 |OAuth 2.0 authentication vulnerabilities  |  OAuth account hijacking via redirect_uri|PRACTITIONER   | N/A |
| 51 | 2026-07-21 |OAuth 2.0 authentication vulnerabilities  |  Stealing OAuth access tokens via an open redirect|PRACTITIONER   | N/A |
| 52 | 2026-07-22 |OAuth 2.0 authentication vulnerabilities  |  SSRF via OpenID dynamic client registration|PRACTITIONER   | N/A |
| 53 | 2026-07-22 |Race conditions  |  Limit overrun race conditions|APPRENTICE   | N/A |
| 54 | 2026-07-22 |Race conditions  |  Bypassing rate limits via race conditions|PRACTITIONER   | N/A |