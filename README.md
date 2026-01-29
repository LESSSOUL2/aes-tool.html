🔐 Encryption Decryption Helper

A client‑side, browser‑only encryption & decryption playground built for learning, testing, and solving encrypted events.

This tool runs entirely in your browser. No servers. No data collection. No keys are stored.

Live Demo (GitHub Pages):
👉 https://L3SSSOUL.github.io/encryption-decryption-tool/


---

✨ Features

🔒 Encrypt / Decrypt

Algorithms: AES, DES, TripleDES

Modes: CBC, CFB, ECB, OFB

Optional IV input

Deterministic IV toggle

Realtime encryption & decryption


🧠 Analyze

Base64 detection

Binary vs readable output detection

Block‑size compatibility hints (e.g. AES 16‑byte blocks)

Entropy heuristics


🧩 Decoy Analysis

Analyzes hint / context text

Ranks keywords by frequency

Flags likely decoy hints

Sends top candidates to Key Guesser


🔑 Key Guesser

Context‑based key hypothesis testing

Key variants generation

Multi‑algorithm & multi‑mode support

IV strategy selection

Confidence scoring (heuristic)


🔬 Test Lab (Unrestricted)

Manual wordlist testing

Adjustable attempt count & rate

IV strategy selection

No artificial limits (user‑controlled)


🔁 Utilities

Base64 encode / decode

HEX encode / decode

Hashing: SHA256, SHA1, MD5



---

🧪 What this tool does

Assists human reasoning in cryptography

Helps analyze encrypted event puzzles

Acts as a crypto learning playground

Allows controlled experimentation


🚫 What this tool does not do

No automatic cracking

No brute‑force wordlists

No scraping websites or social media

No background computation

No guarantee of correct keys


> This tool assists analysis — it does not replace cryptographic understanding.




---

🛡️ Security & Privacy

100% client‑side (HTML + JavaScript)

No backend

No analytics

No logging

No key storage


Everything stays on your device.


---

🚀 How to Use

1. Paste encrypted or plaintext into the relevant panel


2. Select algorithm, mode, key, and IV (if known)


3. Use Analyze to understand structure


4. Use Decoy Analysis to filter misleading hints


5. Use Key Guesser to test hypotheses


6. (Optional) Use Test Lab for experimentation




---

📦 Deployment (GitHub Pages)

This project is a single‑file app.

To deploy:

1. Create a GitHub repository


2. Upload index.html


3. Enable GitHub Pages (main branch, root)



That’s it.


---

⚠️ Disclaimer

This tool is intended for:

education

research

puzzle solving


You are responsible for how you use it.


---

👤 Author

Built by @L3SSSOUL
X (Twitter): https://x.com/L3SSSOUL


---

🏷️ Version

v2.7.2 — Unrestricted


---

If you have ideas, improvements, or want to extend this tool — feel free to fork and experiment.
