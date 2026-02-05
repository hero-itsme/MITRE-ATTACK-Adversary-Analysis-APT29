 Technique Analysis — APT29

T1110 — Brute Force

 Meaning
Brute force involves repeatedly attempting authentication using multiple password combinations to gain unauthorized access.

APT29 Usage
APT29 has conducted password spraying and credential guessing attacks against enterprise email accounts and remote services.

Detection
- Multiple failed authentication attempts
- Successful login following repeated failures
- Authentication attempts from unusual locations

---

 T1001 — Data Obfuscation

 Meaning
Data obfuscation is used to modify data or communication patterns to evade detection by security monitoring tools.

APT29 Usage
APT29 has used obfuscation techniques, including steganography and encoded communications, to conceal command-and-control traffic between implants and C2 servers.

Detection
- Unusual outbound HTTP/HTTPS traffic
- Encoded or anomalous network traffic
- Network activity not matching process behavior

---

T1036 — Masquerading

 Meaning
Masquerading occurs when malicious files or processes are disguised as legitimate system components.

APT29 Usage
APT29 has renamed malicious executables and scheduled tasks to resemble legitimate system or application files.

Detection
- Legitimate-looking binaries running from unusual directories
- Suspicious startup scripts or cron jobs
- File execution from temporary or shared memory locations
