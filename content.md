# Content placeholders for your resume site

This file is a convenient place to paste text extracted from your PDF resume. The template `index.html` pulls content from static HTML — paste or edit the sections below and copy them into the corresponding places in `index.html` or `resume-replica.html`.

---

## About

(Replace with your summary / elevator pitch)

## Research Interests

- Brain-Inspired Foundation Models
- Spiking Neural Networks
- World Models for Robotics

## Experience

### Software Engineer — Company (2020 — Present)
- Bullet 1
- Bullet 2

### Junior Engineer — Startup (2019 — 2020)
- Bullet 1
- Bullet 2

## Projects

- Project A — short description
- Project B — short description

## Publications

- Publication 1 — citation
- Publication 2 — citation

## Contact

Email: salman@example.com
GitHub: https://github.com/salmanabbasi36

---

How to extract text from the PDF locally (Windows):

1) Install Poppler for Windows (provides `pdftotext`).
2) Run in PowerShell:

```powershell
Set-Location -Path 'D:\python\ai_agents\salmanabbasi36.github.io'
pdftotext "Salman Khan Resume.pdf" resume.txt
notepad resume.txt
```

Or use Python with `pdfminer.six`:

```powershell
python -m pip install pdfminer.six
python - <<'PY'
from pdfminer.high_level import extract_text
print(extract_text('Salman Khan Resume.pdf'))
PY
```

Paste the extracted text into the sections above, then copy into the HTML pages or tell me and I'll parse and insert it for you.
