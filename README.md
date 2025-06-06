# System and Network Security Labs

These labs were completed as part of the *System and Network Security* course. Each lab focuses on specific security concepts ranging from basic Linux and web security to advanced attacks like XSS, CSRF, SQL injection, and packet spoofing. The goal is to develop a hands-on understanding of vulnerabilities, their exploitation, and mitigation techniques.

---

## Table of Contents
- [Lab 1 - Bandit Wargame CTF](#lab-1---bandit-wargame-ctf)
- [Lab 2 - Environment Variables & SetUID](#lab-2---environment-variables--setuid)
- [Lab 3 - Buffer Overflow](#lab-3---buffer-overflow)
- [Lab 4 - Natas Web Security](#lab-4---natas-web-security)
- [Lab 5 - CSRF Attack](#lab-5---csrf-attack)
- [Lab 6 - XSS](#lab-6---xss)
- [Lab 7 - SQL Injection](#lab-7---sql-injection)
- [Lab 8 - Sniffing & Spoofing](#lab-8---sniffing--spoofing)

---

## Lab 1 - Bandit Wargame CTF
**Link:** [Bandit Wargame](https://overthewire.org/wargames/bandit/)  
**Submission:** `Bandit Wargame CTF.pdf`

This CTF-style game introduces basic Linux commands and file system navigation. Each level reveals a new password hidden using Unix utilities and permissions.

**Skills Practiced:**
- Navigating Linux file systems  
- Using commands like `cat`, `grep`, `find`, `file`, `ssh`, `nc`, `strings`  
- Understanding file permissions and symbolic links

---

## Lab 2 - Environment Variables & SetUID
**Lab Setup:** [Download Lab Files](https://seedsecuritylabs.org/Labs_20.04/Files/Environment_Variable_and_SetUID/Labsetup.zip)  
**Submission:** `Environment_Variable_and_SetUID.pdf`

This lab demonstrates how environment variables and SetUID programs can be exploited to escalate privileges, and how to mitigate these risks.

**Topics Covered:**
- Understanding SetUID mechanisms  
- Exploiting `PATH` environment variable vulnerabilities  
- Defending against environment-based privilege escalation

---

## Lab 3 - Buffer Overflow
**Submission:** `Buffer_Overflow_Setuid.pdf`

This lab explores how buffer overflow vulnerabilities can be used to alter a program's execution flow and gain control over a system.

**Topics Covered:**
- Writing exploit code for stack-based buffer overflows  
- Identifying vulnerable C code  
- Understanding memory layout and instruction pointers  
- Countermeasures: Stack canaries, ASLR, and non-executable stack

---

## Lab 4 - Natas Web Security
**Link:** [Natas Wargame](https://overthewire.org/wargames/natas/)  
**Submission:** `Natas Web Security.pdf`

This web security game provides hands-on experience with server-side vulnerabilities.

**Topics Covered:**
- HTML source inspection  
- HTTP headers manipulation  
- Path traversal  
- Command injection and SQLi basics  
- Encryption bypass and logic flaws

---

## Lab 5 - CSRF Attack
**Lab Setup:** [Web_CSRF_Elgg](https://seedsecuritylabs.org/Labs_20.04/Web/Web_CSRF_Elgg/)  
**Submission:** `Web_CSRF_Elgg.pdf`

This lab uses a vulnerable Elgg social network to demonstrate CSRF attacks.

**Topics Covered:**
- GET and POST request manipulation  
- Forging unauthorized friend requests and profile changes  
- Mitigation using CSRF tokens and SameSite cookie attributes  
- Dockerized environment with attacker and victim setups

---

## Lab 6 - XSS
**Lab Setup:** [Web_XSS_Elgg](https://seedsecuritylabs.org/Labs_20.04/Web/Web_XSS_Elgg/)  
**Submission:** `Web_XSS_Elgg.pdf`

This lab explores how malicious JavaScript can be injected into web applications using XSS vulnerabilities.

**Topics Covered:**
- Persistent and reflective XSS  
- Session hijacking through cookies  
- Writing self-propagating worms  
- Content Security Policy (CSP) implementation

---

## Lab 7 - SQL Injection
**Lab Setup:** [Web_SQL_Injection](https://seedsecuritylabs.org/Labs_20.04/Web/Web_SQL_Injection/)  
**Submission:** `Web_SQL_Injection.pdf`

This lab focuses on SQL injection attacks, showing how attackers can extract or manipulate database contents through vulnerable inputs.

**Topics Covered:**
- Union-based and error-based SQLi  
- Authentication bypass  
- Input sanitization and prepared statements  
- Observing attack payloads and defense mechanisms

---

## Lab 8 - Sniffing & Spoofing
**Lab Set**
