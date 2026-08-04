# Steganography

Steganography is the practice of hiding a secret message, file, or image inside another file or physical object to avoid detection. Unlike cryptography, which scrambles a message so people cannot read it, steganography hides the fact that a secret message even exists.

---

## 🎯 Purpose of this Repository

This repository serves as a curated collection, knowledge base, and testing hub for various steganography techniques and tools. The main goals are:
* **Tool Curation:** Centralizing links and documentation for reliable steganography and steganalysis tools.
* **Testing & Verification:** Keeping track of hands-on tests, benchmarks, and visual results.
* **Educational Resource:** Providing a structured environment to study how data hidden in different carrier media behaves under analysis.

## 📂 Repository Structure

The project follows a clean, documentation-focused structure:

```text
steganography-resources/
├── .gitignore            # Prevents untracked media files from being committed
├── LICENSE               # MIT License (Permissive open-source terms)
├── README.md             # Repository documentation and tool index
└── assets/               # Screenshots, diagrams, and benchmark visuals
    ├── benchmark-results.png
    └── toolkit-preview.png
```

---

## 🛠️ Tools & Resources

### Image Steganography & Steganalysis
*   [Steghide](https://sourceforge.net) - A classic command-line tool used to hide data in BMP, WAV, and AU files using a passphrase.
*   [Stegsolve](https://github.com) - A widely used Java-based GUI tool for analyzing image layers, bit planes, and detecting hidden data visually (essential for CTFs).
*   [Aperi'Solve](https://aperisolve.com) - A powerful web-based platform that automates layer analysis, zsteg, steghide, and exiftool checks in one single upload.
*   [zsteg](https://github.com) - A command-line tool written in Ruby specifically designed to detect hidden data in PNG and BMP files via LSB (Least Significant Bit) techniques.

### Audio & Video Steganography
*   [DeepSound](https://jjtc.com) - A user-friendly Windows GUI tool that hides encrypted data within audio files (like WAV or FLAC) without altering sound quality.
*   [OpenStego](https://openstego.com) - An open-source Java tool that supports data hiding (using robust watermarking algorithms) inside images and audio carriers.

### File Metadata & Carving
*   [ExifTool](https://exiftool.org) - A command-line utility used to read, write, and modify metadata information (EXIF, IPTC, XMP) in almost any file type.
*   [Binwalk](https://github.com) - A fast tool for searching, analyzing, and extracting hidden files, payloads, or embedded code embedded inside firmware images or standard files.

---

## ⚖️ Legal Disclaimer

This repository is created strictly for **educational, research, and security auditing purposes**. 
* The author is not responsible for any misuse, damage, or illegal activities caused by the tools or information listed here. 
* Users are entirely responsible for ensuring compliance with local laws and regulations before testing or utilizing any software linked in this documentation.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this documentation as long as the original copyright notice is included.
