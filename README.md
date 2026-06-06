# Rahul CV Generator

Personal AI-powered CV tailoring tool. Paste a job description, get a tailored ATS-optimised `.docx` CV instantly.

## How it works
1. Enter your Anthropic API key (stored locally in browser)
2. Paste the full job description
3. Choose colour theme and CV length
4. Click Generate → Download `.docx`

## Deploy to GitHub Pages
```bash
git clone https://github.com/rahulchhallare/cv-generator
cd cv-generator
# copy index.html here
git add . && git commit -m "init" && git push
# Enable GitHub Pages: Settings → Pages → Branch: main → /root
```

## Tech
- Claude Sonnet API for JD analysis & tailoring
- docx.js for Word document generation
- Pure HTML/CSS/JS — no build step, no server
