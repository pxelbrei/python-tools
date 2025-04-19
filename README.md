1. Port Scanner
Purpose: Scans a target IP for open ports (like a simple nmap).
Key Features:
<br>
Uses socket to check TCP ports.
<br>
Customizable port range (e.g., 20–80).
Use Case: Network reconnaissance during penetration testing.
<br>
2. Password Cracker (Dictionary Attack)
Purpose: Attempts to crack MD5 hashes using a wordlist.
Key Features:
<br>
Reads passwords from a file (wordlist.txt).
<br>
Compares MD5 hashes of words to the target hash.
Use Case: Ethical password recovery (authorized testing only).
<br>
3. File Integrity Checker (SHA-256)
Purpose: Generates a SHA-256 hash for file integrity verification.
Key Features:
<br>
Detects tampering by comparing hashes.
<br>
Reads files in chunks (memory-efficient).
Use Case: Ensuring critical files (e.g., system binaries) are unmodified.
<br>
4. Wi-Fi Security Scanner
Purpose: Lists nearby Wi-Fi networks and their encryption types.
Key Features:
<br>
Runs netsh (Windows) to fetch SSIDs and authentication methods.
<br>
Uses regex to parse network details.
Use Case: Auditing wireless network security.
<br>
5. Log Analyzer (Brute-Force Detection)
Purpose: Identifies suspicious IPs with multiple failed login attempts.
Key Features:
<br>
Parses log files (e.g., auth.log) for "Failed login" patterns.
<br>
Flags IPs exceeding a threshold (default: 5 attempts).
Use Case: Detecting brute-force attacks on servers.
<br>
Notes:
Legal Use: Only test systems you own/have permission to audit.
