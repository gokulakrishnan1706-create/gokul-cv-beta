# GokulCV — AI Adaptive CV Generator

A personal AI-powered CV generator that takes a job description and instantly produces a tailored, ATS-optimised CV.

## How it works
1. Enter your Anthropic API key
2. Select Part-Time or Full-Time role type
3. Paste the job description
4. Click Generate — Claude tailors your CV in seconds
5. Download as PDF

## Stack
- Pure HTML/CSS/JS — no framework, no build step
- Claude API (claude-sonnet) for intelligent tailoring
- html2canvas + jsPDF for PDF export
- Deployed on Vercel as a static site

## Deploy
```bash
git clone https://github.com/gokulakrishnan1706/gokulcv
cd gokulcv
vercel deploy
```
