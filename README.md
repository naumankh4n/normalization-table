Unicode Variants for Cybersecurity Testing

A curated repository of Unicode character variants for multiple characters, designed to help security researchers, developers, and bug hunters test for Unicode normalization vulnerabilities, homograph attacks, and character obfuscation in software systems.

🚀 Purpose

Unicode characters can have many visually similar variants across different scripts, diacritics, and styles. These variants are often abused in:

    Homograph attacks: Spoofing domain names, usernames, and file names.

    Unicode normalization issues: Bypassing input validation, filters, and security controls.

    Phishing and social engineering: Confusing users by visually deceptive characters.

This repository provides collections of variants for various base characters to facilitate:

    Security testing & pentesting

    Development of normalization-safe applications

    Research and education on Unicode-based attack vectors

📦 Contents

    Unicode variant lists for multiple characters (e.g., e, a, o, i, c, etc.)

    Each character’s variants stored in separate text files (one variant per line)

    README with usage instructions and context

🔍 Use Cases

    Test input validation systems and filters for proper Unicode normalization (NFC, NFD, NFKC, NFKD)

    Detect and prevent homograph attacks in domains, emails, usernames, or code identifiers

    Generate test payloads for fuzzing and penetration testing

    Educate teams about Unicode pitfalls in security
