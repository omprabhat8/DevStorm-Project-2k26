# DevStorm Project 2k26 – Password Strength & Breach Checker

Checks how strong a password is and whether it appears in known data breaches.

## How it works
- Hashes the password (SHA-1) and sends only the first 5 characters of the hash
  to a breached-passwords API (k-anonymity), so the full password is never shared.
- Shows whether the password was found in breaches and rates its strength.

## Built with
Python, JavaScript, HTML

## Team
Built at the DevStorm hackathon (2026) by PHOENIX CODERS
