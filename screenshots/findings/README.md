# Findings Summary

The following table summarizes the major vulnerabilities identified during the DVWA Web Application Security Assessment.

| # | Finding | Severity | CVSS | Component |
|---|---------|----------|------|-----------|
| 1 | SQL Injection | Critical | 8.8 | `/sqli/` |
| 2 | File Upload / Remote Code Execution (RCE) | Critical | 9.0 | `/upload/` |
| 3 | Stored Cross-Site Scripting (XSS) | High | 7.4 | `/xss_s/` |
| 4 | Reflected Cross-Site Scripting (XSS) | High | 6.1 | `/xss_r/` |
| 5 | Cross-Site Request Forgery (CSRF) | High | 6.5 | `/csrf/` |
| 6 | No Account Lockout (Brute Force) | Medium | 5.3 | `/login.php` |
| 7 | Missing Security Headers | Medium | 5.3 | All Pages |
| 8 | PHP Information Disclosure | Medium | 5.3 | `/phpinfo.php` |
| 9 | Session Cookie Missing HttpOnly Flag | Low | 4.3 | Session Cookies |

---

## Notes

- Testing was performed in a **controlled DVWA laboratory environment**.
- Risk ratings are based on the observed impact within the lab.
- Supporting screenshots for each finding are available in the corresponding folders under the `screenshots` directory.
