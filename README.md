# CTF Write-Ups

A curated collection of write-ups for Capture The Flag (CTF) challenges I've completed across various platforms and competitions.

## 📋 About

This repository serves as a comprehensive archive of my CTF journey, documenting solutions, methodologies, and lessons learned from different cybersecurity challenges. Each write-up includes detailed explanations of the problem-solving process, tools used, and key takeaways.

## 🎯 Platforms

- **PicoCTF** - Educational CTF platform by Carnegie Mellon University
- **Additional platforms** as I continue to explore more CTF competitions

## 📁 Repository Structure

```
CTF-Write-Ups/
├── PicoCTF/
│   ├── Bytemancy 1/
│   │   └── README.md
│   ├── images/
│   │   ├── bytemancy-1-ascii-converter.png
│   │   ├── bytemancy-1-challenge.png
│   │   ├── bytemancy-1-flag.png
│   │   ├── bytemancy-1-prompt.png
│   │   ├── bytemancy-1-repeat-text.png
│   │   ├── my-git-challenge.png
│   │   ├── my-git-clone-readme.png
│   │   ├── my-git-push-flag.png
│   │   └── undo-full-session.png
│   ├── MY GIT/
│   │   └── README.md
│   └── Undo/
│       └── README.md
├── TEMPLATE.md
└── README.md
```

**Write-Ups:**

| Platform | Challenge | Category | Status |
|----------|-----------|----------|--------|
| PicoCTF | [Bytemancy 1](PicoCTF/Bytemancy%201/README.md) | General Skills | Complete |
| PicoCTF | [Undo](PicoCTF/Undo/README.md) | General Skills | Complete |
| PicoCTF | [MY GIT](PicoCTF/MY%20GIT/README.md) | General Skills | Complete |

**Structure Guidelines:**
- Each challenge/room/machine should have its own folder containing a `README.md`
- Store each platform's screenshots in a shared `images/` folder at the platform level (e.g. `PicoCTF/images/`) and prefix each file with the challenge name (e.g. `undo-full-session.png`) so it's clear which write-up it belongs to
- Link to those images from a challenge's `README.md` with a relative path (e.g. `../images/undo-full-session.png`)
- Use `TEMPLATE.md` as a starting point for new write-ups

## 🏆 Categories

Common CTF challenge categories covered:

- **Binary Exploitation** - Buffer overflows, format strings, etc.
- **Cryptography** - Encryption, hashing, encoding challenges
- **Forensics** - File analysis, steganography, memory dumps
- **Reverse Engineering** - Binary analysis, decompilation
- **Web Exploitation** - SQL injection, XSS, CSRF, etc.
- **General Skills** - Basic challenges and miscellaneous tasks
- **OSINT** - Open-source intelligence gathering
- **Pwn** - Exploitation challenges

## 📝 Write-Up Template

Each challenge write-up typically includes:

1. **Challenge Name & Points**
2. **Description** - Original challenge description
3. **Category** - Challenge type
4. **Solution** - Step-by-step walkthrough
5. **Flag** - The captured flag (if safe to share)
6. **Tools Used** - Software and scripts utilized
7. **Lessons Learned** - Key takeaways and notes

## 🛠️ Common Tools

Tools frequently used in these challenges:

- `netcat`, `nmap`, `Wireshark`
- `Burp Suite`, `sqlmap`, `dirb`
- `pwntools`, `gdb`, `ghidra`, `radare2`
- `John the Ripper`, `hashcat`, `CyberChef`
- `binwalk`, `exiftool`, `strings`
- `Python`, `bash` scripting

## 🚀 Getting Started

To explore a write-up:

1. Navigate to the relevant platform folder
2. Choose the challenge you're interested in
3. Read the `README.md` for the complete solution

## ⚠️ Disclaimer

These write-ups are published **after** CTF competitions have concluded and are intended for educational purposes only. Please respect the rules of active competitions and avoid sharing solutions during ongoing events.

## 🤝 Contributing

This is a personal repository, but if you find errors or have suggestions for improvement, feel free to open an issue.

## 📫 Contact

- GitHub: [@ObsidianNull](https://github.com/ObsidianNull)

## 📜 License

This repository is for educational purposes. Please use responsibly and ethically.

---

**Last Updated:** September 2026
