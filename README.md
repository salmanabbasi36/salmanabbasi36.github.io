# salmanabbasi36.github.io


This repository hosts the resume site for Salman Khan using GitHub Pages. It now contains a responsive academic-style template inspired by an academic personal site. Files to edit:

- `index.html` — main site (sidebar + content). Edit content sections directly here.
- `styles.css` — site styles and print rules.
<!-- `resume-replica.html` removed — use `index.html` and `resume-embed.html` instead. -->
- `Salman Khan Resume.pdf` — your original PDF (kept in the repo).
- `content.md` — a helper file with placeholders where you can paste extracted text from your PDF.

Quick workflow
- To use your photo, add `images/avatar.jpg` or replace `images/avatar.svg`.
- To extract text from the PDF locally, use `pdftotext` (Poppler) or `pdfminer.six` (Python). See `content.md` for commands.
- Edit `index.html` (or `resume-replica.html`) and commit the changes:

```powershell
Set-Location -Path 'D:\python\ai_agents\salmanabbasi36.github.io'
git add .
git commit -m "Update site content"
git push origin main
```

If pushing from this environment fails due to network issues, run the commands above locally in PowerShell and authenticate with GitHub (PAT recommended).

If you want, tell me to extract/paste the PDF text into the site and I'll do it for you (I may need the extracted text pasted into the chat if automated extraction isn't available from here).
