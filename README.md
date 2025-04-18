# 🔐 HashChecker

**HashChecker** is a Python-based utility designed to generate and verify cryptographic hash values for files and text inputs. It supports popular hashing algorithms such as MD5, SHA-1, and SHA-256, making it a versatile tool for integrity checks and file validation. Users can input either a file path or a plain text string, and the tool will compute the corresponding hash based on the selected algorithm. Additionally, HashChecker allows users to compare the computed hash with a known or expected hash value, making it useful for confirming that files haven't been corrupted or tampered with. Built on Python's hashlib and argparse libraries, it requires no external dependencies and can be easily run from the command line, offering a simple yet powerful solution for hash verification tasks.

---

## ✅ Features

- File integrity verification
- Supports `md5`, `sha1`, and `sha256`
- Command-line interface (CLI)
- Lightweight and beginner-friendly

---

## 📦 Requirements

- Python 3.6+

No external libraries needed — uses Python's built-in `hashlib` and `argparse`.

---

##  Getting Started:

### 🔧 Clone the repo

```bash
git clone https://github.com/jordanstewart-hub/hashchecker.git
cd hashchecker
```

### ▶️ Run the script

```bash
python hashchecker.py --file sample.txt --hash <expected_hash> --algo sha256
```

---

##  Example Usage

```bash
python hashchecker.py --file sample.txt \
                      --hash e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855 \
                      --algo sha256
```

**Output:**

```
Computed sha256 hash: e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
✅ Hash match: File integrity verified.
```

---

## Project Structure

```
hashchecker/
├── hashchecker.py         # Main hash checker script
├── README.md              # Documentation
└── sample.txt             # Sample file to test hash verification
```

---

## ⚠️ DISCLAIMER ⚠️

This tool is for educational and integrity checking purposes only. It does not protect against malware or security breaches on its own.





Created by: **[Jordan Stewart]**

