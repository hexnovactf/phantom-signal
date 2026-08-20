# ⚡ Phantom Signal

> *"In the static of forgotten frequencies, a signal persists. But this time, the ghost shattered its message into pieces and scattered them across the void. Only those who can trace every fragment will hear the full whisper..."*

---

## 🎯 Challenge: Phantom Signal — Fragmented Ghost

| Detail | Info |
|--------|------|
| **Category** | OSINT / Recon + Cryptography |
| **Points** | 500 |
| **Difficulty** | 🔴 Hard |
| **Flag Format** | `HEXNOVA{...}` |
| **Platform** | [HexNova CTF](https://hexnova.space) |

---

## 📡 Briefing

A phantom once whispered its secret in a single breath. But the signal was intercepted, **fragmented**, and scattered across the digital graveyard.

Our intelligence indicates:
- The ghost's original transmission was **split into 4 fragments**.
- Each fragment was **encoded differently** before being hidden.
- The fragments were concealed in **pull requests** from an unknown collaborator.
- You must **find all fragments**, **decode each one**, and **reassemble** them in the correct order.

> ⚠️ *"The signal is never where you expect it. Look where others contribute, not where they build."*

---

## 🔍 What You Know

```
Input Hash     : 42697e23c7a0a4fefcaaf440e3209180
Hash Algorithm : MD5
Cipher Layer   : ROT-13 (applied before hashing)
Fragments      : 4 pieces, each encoded differently
```

---

## 💡 Hints

<details>
<summary>Hint 1 (Free)</summary>

*"Forks are not just for eating. In the world of code, a fork remembers what the original tries to forget..."*

</details>

<details>
<summary>Hint 2 (-75 points)</summary>

*"Pull requests are public conversations. Read between the lines — literally."*

</details>

<details>
<summary>Hint 3 (-100 points)</summary>

The 4 fragments use these encodings (not in order): `Base64`, `Hexadecimal`, `Binary (ASCII)`, `ROT-13`

</details>

<details>
<summary>Hint 4 (-150 points)</summary>

Look for HTML comments `<!-- -->` — ghosts hide in the invisible.

</details>

---

## 📜 Rules

- Standard CTF rules apply.
- No brute-forcing the CTF platform.
- The flag is case-sensitive.
- Fragments must be assembled in the correct order.
- Submit in `HEXNOVA{...}` format.

---

## 🗂️ Files

| File | Description |
|------|-------------|
| `word.txt` | A wordlist of 100 entries — some are decoys, some are clues |

---

## 🏗️ Built for

[![HexNova CTF](https://img.shields.io/badge/HexNova-CTF-brightgreen)](https://hexnova.space)

> Created by **hexnovactf** • Modern Capture The Flag Platform
