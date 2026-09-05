# PortSwigger Web Security Academy - Solved Labs

![Total Labs](https://img.shields.io/badge/Total%20Labs%20Solved-86-blue) ![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--09--05  -yellow) ![Level](https://img.shields.io/badge/Level-NEWBIE-green) ![Vulnerability labs](https://img.shields.io/badge/Completed-31%25-purple)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress
- **Apprentice**: 21 of 61
- **Practitioner**: 57 of 174
- **Expert**: 2 of 39

## Categories Covered

- **Authentication vulnerabilities**: 12/14 lab
- **SQL injection**: 5/18 lab
- **Access control**: 13/13 lab
- **Path traversal**: 6/6 lab
- **Command injection**: 5/5 lab
- **File upload vulnerabilities**: 6/7 lab
- **OAuth 2.0 authentication vulnerabilities**: 5/6 lab
- **Race conditions**: 4/6 lab
- **Server-side request forgery (SSRF)**: 6/7 lab
- **API testing**: 2/5 lab
- **Cross-site request forgery (CSRF)**: 11/12 lab
- **DOM-based vulnerabilities**: 1/7 lab
- **Server-side template injection**: 6/7 lab
- **Clickjacking**: 4/5 lab

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
| 55 | 2026-07-26 |Race conditions  |  Single-endpoint race conditions|PRACTITIONER   | N/A |
| 56 | 2026-07-26 |Race conditions  |  Exploiting time-sensitive vulnerabilities|PRACTITIONER   | N/A |
| 57 | 2026-07-30 |Server-side request forgery (SSRF)  |  Basic SSRF against the local server|APPRENTICE   | N/A |
| 58 | 2026-07-30 |Server-side request forgery (SSRF)  |  Basic SSRF against another back-end system|APPRENTICE   | N/A |
| 59 | 2026-07-30 |Server-side request forgery (SSRF)  |  SSRF with blacklist-based input filter|PRACTITIONER   | [Writeup](https://medium.com/@afgjr/portswigger-lab-write-up-ssrf-with-blacklist-based-input-filter-492ba0c0aa85) |
| 60 | 2026-08-01 |Server-side request forgery (SSRF)  |  SSRF with filter bypass via open redirection vulnerability|PRACTITIONER   | N/A |
| 61 | 2026-08-01 |Server-side request forgery (SSRF)  |  Blind SSRF with out-of-band detection|PRACTITIONER   | N/A |
| 62 | 2026-08-02 |Server-side request forgery (SSRF)  |  Blind SSRF with Shellshock exploitation|EXPERT   | N/A |
| 63 | 2026-08-08 |API testing |  Exploiting an API endpoint using documentation|APPRENTICE   | N/A |
| 64 | 2026-08-08 |API testing |  Finding and exploiting an unused API endpoint|PRACTITIONER   | N/A |
| 65 | 2026-08-26 |Cross-site request forgery (CSRF) |  CSRF vulnerability with no defenses|APPRENTICE   | N/A |
| 66 | 2026-08-26 |Cross-site request forgery (CSRF) |  CSRF where token validation depends on request method|PRACTITIONER   | N/A |
| 67 | 2026-08-26 |Cross-site request forgery (CSRF) |  CSRF where token is not tied to user session|PRACTITIONER   | N/A |
| 68 | 2026-08-26 |Cross-site request forgery (CSRF) |  CSRF where token validation depends on token being present|PRACTITIONER   | N/A |
| 69 | 2026-08-26 |Cross-site request forgery (CSRF) |  CSRF where token is tied to non-session cookie|PRACTITIONER   | N/A |
| 70 | 2026-08-27 |Cross-site request forgery (CSRF) |  CSRF where token is duplicated in cookie|PRACTITIONER   | N/A |
| 71 | 2026-08-27 |Cross-site request forgery (CSRF) |  SameSite Lax bypass via method override|PRACTITIONER   | N/A |
| 72 | 2026-08-28 |Cross-site request forgery (CSRF) |  SameSite Strict bypass via client-side redirect|PRACTITIONER   | N/A |
| 73 | 2026-08-28 |DOM-based vulnerabilities|  DOM-based open redirection|PRACTITIONER   | N/A |
| 74 | 2026-08-29 |Cross-site request forgery (CSRF)|  CSRF with broken Referer validation|PRACTITIONER   | N/A |
| 75 | 2026-08-29 |Cross-site request forgery (CSRF)|  CSRF where Referer validation depends on header being present|PRACTITIONER   | N/A |
| 76 | 2026-08-29 |Cross-site request forgery (CSRF)|  SameSite Strict bypass via sibling domain|PRACTITIONER   | N/A |
| 77 | 2026-09-03 |Server-side template injection|  Server-side template injection in an unknown language with a documented exploit|PRACTITIONER   | N/A |
| 78 | 2026-09-03 |Server-side template injection|  Basic server-side template injection|PRACTITIONER   | N/A |
| 79 | 2026-09-03 |Server-side template injection|  Basic server-side template injection (code context)|PRACTITIONER   | N/A |
| 80 | 2026-09-03 |Server-side template injection|  Server-side template injection using documentation|PRACTITIONER   | N/A |
| 81 | 2026-09-04 |Server-side template injection|  Server-side template injection with information disclosure via user-supplied objects|PRACTITIONER   | N/A |
| 82 | 2026-09-04 |Clickjacking|  Basic clickjacking with CSRF token protection|APPRENTICE   | N/A |
| 83 | 2026-09-04 |Clickjacking|  Clickjacking with form input data prefilled from a URL parameter|APPRENTICE   | N/A |
| 84 | 2026-09-05 |Clickjacking|  Clickjacking with a frame buster script|APPRENTICE   | N/A |
| 85 | 2026-09-05 |Clickjacking|  Exploiting clickjacking vulnerability to trigger DOM-based XSS|PRACTITIONER   | N/A |
| 86 | 2026-09-05 |Server-side template injection|  Server-side template injection in a sandboxed environment|Expert   | N/A |

