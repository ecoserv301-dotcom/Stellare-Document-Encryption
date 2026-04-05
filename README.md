# ✦ Stellare Document Encryption v6
### Military-Grade File Encryption for Windows
**Version 6 · Windows 10 / 11 · Standard £9 · Advanced £29 · Professional £59 · One-time purchase**

---

Stellare Document Encryption protects any file using a triple-pass cipher stack — AES-256, ChaCha20, and AES-256 — with Argon2id key derivation. Three editions unlock progressively stronger protection in the same application. One download. Your licence key determines which edition is active.

---

## Editions

| Feature | Standard £9 | Advanced £29 | Professional £59 |
|---|:---:|:---:|:---:|
| One-time purchase | ✓ | ✓ | ✓ |
| Machine-locked licence | ✓ | ✓ | ✓ |
| Password + Unlock Code | ✓ | ✓ | ✓ |
| Double AES-256-CBC | ✓ | ✓ | ✓ |
| Argon2id Key Derivation | ✓ | ✓ | ✓ |
| Protected Nonce Storage | ✓ | ✓ | ✓ |
| Session Memory (Reboot-Cleared) | ✓ | ✓ | ✓ |
| File & Folder Encryption | ✓ | ✓ | ✓ |
| Right-Click Context Menu | ✓ | ✓ | ✓ |
| Second Code Layer | — | ✓ | ✓ |
| Triple-Pass AES+ChaCha20+AES | — | ✓ | ✓ |
| Simple Key File (.stkf) | — | ✓ | ✓ |
| Key-File-Bound Nonce Protection | — | ✓ | ✓ |
| KFM Salt Mixing (Argon2id) | — | ✓ | ✓ |
| 5-Key Independent Derivation | — | ✓ | ✓ |
| Advanced Key File System | — | — | ✓ |
| KFM-Controlled Encryption Depth | — | — | ✓ |
| Defaced Hash Verification | — | — | ✓ |
| Unnamed Island Security | — | — | ✓ |
| Forensic Resistance | — | — | ✓ |
| Anti Brute-Force Architecture | — | — | ✓ |
| **Stellare Document Converter Pro (FREE)** | — | — | ✓ |

---

## How It Works

### Argon2id Key Derivation
All editions use Argon2id — the winner of the Password Hashing Competition and the algorithm recommended by OWASP and NIST. Argon2id is memory-hard, meaning GPU and ASIC acceleration provides minimal advantage. Every encrypted file receives a unique cryptographically random salt — two identical files encrypted with the same credentials produce completely different ciphertext every time.

### Standard — Double AES-256-CBC
Password and Code are processed through Argon2id to derive two independent AES keys. Breaking the outer layer reveals only another AES-256 ciphertext with a completely different key — the attack must start over from scratch.

### Advanced — Triple-Pass Cipher
Password, Code, and Second Code derive five independent 32-byte keys from a single 160-byte Argon2id output. Encryption applies three passes: AES-256 → ChaCha20 → AES-256. AES and ChaCha20 are from entirely different cryptographic families — a theoretical breakthrough against one provides zero assistance attacking the other.

### Professional — KFM-Controlled Encryption Depth
The Advanced Key File system uses any existing file on your machine as the key source. KFM-Controlled Encryption Depth means the key file actively determines how many and which type of extra passes are applied. Without the correct key file an attacker cannot know the encryption depth. The content hash is deliberately defaced — forensic analysis cannot confirm the file even contains encrypted data.

---

## Key Features

- **Right-click shell integration** — encrypt or decrypt any file or folder directly from Windows Explorer
- **Session Memory** — credentials saved encrypted with AES-256 and machine-locked, auto-cleared on reboot
- **Per-file random salt** — every encrypted file is unique; rainbow table attacks do not apply
- **No key recovery** — Stellare Software has no access to your passwords, codes, or key files
- **Built-in PDF user manual** — full documentation included in the installer
- **Nuitka compiled** — native binary, no Python runtime distributed
- **Clean install and uninstall** — no residual data or registry junk

---

## Encrypted File Format

Files are saved with the `.sf` (Stellare File) extension. The `SF6K` header contains all metadata required for decryption automatically — you never need to remember settings manually.

---

## Activation

1. Run the installer and launch the application
2. Click **BUY NOW** on your chosen edition — your browser opens the LemonSqueezy checkout
3. Complete payment — your licence key is emailed instantly
4. Return to the software, paste your licence key and click **ACTIVATE**
5. Your edition is detected automatically from your purchase

Your licence is bound to your machine hardware on first activation. To move to a new machine, deactivate at [app.lemonsqueezy.com/my-orders](https://app.lemonsqueezy.com/my-orders) then reactivate using the same key.

---

## Download and Purchase

**[⬇ Download Stellare Document Encryption v6](https://github.com/ecoserv301-dotcom/Stellare-Document-Encryption/raw/refs/heads/main/StellareDocumentEncryptionSetup_v6.exe)**

| Edition | Price | Checkout |
|---|---|---|
| Standard | £9 | [Buy Standard](https://stellare-software.lemonsqueezy.com/checkout/buy/e7f6be3b-b91d-4ed2-92d2-ef11c4b0e257) |
| Advanced | £29 | [Buy Advanced](https://stellare-software.lemonsqueezy.com/checkout/buy/e7f6be3b-b91d-4ed2-92d2-ef11c4b0e257) |
| Professional | £59 | [Buy Professional](https://stellare-software.lemonsqueezy.com/checkout/buy/e7f6be3b-b91d-4ed2-92d2-ef11c4b0e257) |

One-time purchase · Machine-locked licence · Instant delivery via LemonSqueezy

---

## Support

| | |
|---|---|
| Developer | Stellare Software |
| Email | ecoserv301@gmail.com |
| Store | [stellare-software.lemonsqueezy.com](https://stellare-software.lemonsqueezy.com) |
| Licences | [app.lemonsqueezy.com/my-orders](https://app.lemonsqueezy.com/my-orders) |

© 2026 Stellare Software · All Rights Reserved
