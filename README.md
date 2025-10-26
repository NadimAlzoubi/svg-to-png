# 🔐 File Encryption & Decryption (Client-Side)

A simple web tool that lets you **encrypt** and **decrypt** files directly in your browser.  
No server, no upload — **everything happens locally** using the Web Crypto API (AES-GCM 256-bit).

## How to Use
1. Open the `index.html` file in your browser.
2. **Encrypt:**
   - Select a file → Click **Encrypt File**
   - The tool will generate:
     - `yourfile.enc` → encrypted file
     - `yourfile.key` → secret key (save it!)
3. **Decrypt:**
   - Select the `.enc` file + the `.key` file → Click **Decrypt File**

## Features
- 100% local, private, offline
- AES-GCM 256-bit encryption (Web Crypto API)
- No backend or dependencies

## Files
- index.html # UI + encryption/decryption logic in one page

## Important
- **Don't lose the .key** — without it, the file cannot be decrypted.
- Keep the key **separate** from the encrypted file for safety.

---

Made for personal use — feel free to edit or improve 😊
