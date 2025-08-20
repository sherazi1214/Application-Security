# Application Security

**English:**
Application Security means protecting software applications from threats and vulnerabilities during development, deployment, and runtime. It includes secure coding, testing, patching, and monitoring.

**Urdu:**
Application Security ka matlab hai software apps ko vulnerabilities aur attacks se protect karna, jab wo develop ho rahi hoti hain aur jab wo run kar rahi hoti hain.

### Deployment Staging

**English:**
Deployment staging is the process of testing applications in different environments before pushing to production. This ensures bugs or vulnerabilities are caught early.

**Urdu:**
Deployment staging ka matlab hai app ko different environments me test karna production se pehle taa ke koi bug ya vulnerability live users tak na jaye.

### Deployment Staging Steps

**English:**

**Development (Dev):** Code writing, unit testing.

**Testing (QA):** Functional & security testing.

**Staging (Pre-Prod):** Simulates production environment.

**Production (Prod):** Live environment for end users.

**Urdu:**
Deployment staging steps:

**Development:** Developers code likhte hain.

**Testing (QA):** Errors aur vulnerabilities test hote hain.

**Staging:** Pre-production jahan app ko real jaisa test karte hain.

**Production:** Live users ke liye app deploy hoti hai.

### SecDevOps (Secure DevOps)

**English:**
SecDevOps means integrating security into DevOps pipeline (continuous integration & delivery). Instead of testing security at the end, security checks are automated at every step.

**Urdu:**
SecDevOps ka matlab hai DevOps ke har step me security integrate karna. Matlab coding, testing, deployment ke saath saath hi automated security checks lagte hain.

### Static Application Security Testing (SAST)

**English:**

White-box testing

Analyzes source code or binaries before execution.

Detects vulnerabilities like SQL injection, hardcoded credentials, buffer overflows.

**Urdu:**
SAST ek static analysis hoti hai jo code run hone se pehle check karti hai. Ye insecure code patterns (SQL injection, hardcoded passwords) detect karti hai.

### Dynamic Application Security Testing (DAST)

**English:**

Black-box testing

Tests application while running.

Finds runtime issues like authentication bypass, XSS, CSRF, injection flaws.

**Urdu:**
DAST me app ko run karke test karte hain (jaise hacker test kare). Ye vulnerabilities detect karta hai jo runtime me hoti hain (XSS, CSRF, bypass).

### Runtime Application Self-Protection (RASP)

**English:**
RASP is a security technology that sits inside the application and protects it in real time. It monitors inputs/outputs and blocks malicious requests immediately.

**Urdu:**
RASP app ke andar hi chalta hai aur real-time me malicious activity block karta hai. Jaise hi koi attacker exploit try kare, RASP ussi waqt rok leta hai.

### Secure Application Development (Best Practices)

**English:**

Secure Coding Guidelines (OWASP Top 10 awareness).

Use of SAST & DAST tools in CI/CD pipeline.

Threat Modeling before coding.

Dependency Checking (no vulnerable libraries).

Input Validation & Sanitization.

Encryption for sensitive data.

Regular Patching & Updates.

**Urdu:**
Secure development k liye best practices:

Secure coding follow karo (OWASP Top 10)

SAST & DAST automated tools use karo

Threat modeling karo pehle se

Libraries aur dependencies check karo

Input validate aur sanitize karo

Sensitive data encrypt karo

Updates aur patches time pe lagao

##Summary Flow:

**Application Security** = protect apps from vulnerabilities.

**Deployment Staging **= Dev → Test → Staging → Prod.

**SecDevOps** = Security built into DevOps pipeline.

**SAST**= Check source code (before running).

**DAST** = Test live app (runtime).

**RASP** = Real-time in-app protection.

**Secure Development** = Secure coding, patching, testing.
