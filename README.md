# Fica o essencial (Keep the Good Part)

> A free, step-by-step guide for turning YouTube videos, on any topic, into verifiable PDF reports with a prompt that works in Claude or Gemini.

**Website:** https://rcrdo4750.github.io/fica-o-essencial/

---

## What it is

A single page, in European Portuguese and English, that teaches you how to use a prompt to summarize long videos.
You pick your AI assistant and your device, copy the prompt, and follow the steps until you have your first PDF report.

It works with videos on any subject: finance, cooking, DIY, health, study, technology.

## Who it is for

- People without technical knowledge who want to get more out of long videos.
- Anyone who would rather read an organized report than watch an hour of video.
- Anyone who wants to be able to check what a summary claims, instead of trusting it blindly.

## What the guide includes

| Section | What it is for |
|---|---|
| Example | A fictional video and report, so you can see the result before you start |
| Steps | Paths tailored to the AI assistant and device you choose |
| Prompt | The full prompt, in Portuguese and English, with a copy button |
| Saving the PDF | How to save your first report |
| Transcript and MP4 | Alternatives for when the assistant cannot access the video |
| Problems | Help with the most common errors |
| Share | A button to send the guide to someone else |

## How to use it

1. Open the [website](https://rcrdo4750.github.io/fica-o-essencial/).
2. Choose the language, the AI assistant and the device.
3. Copy the prompt with the button in the bottom bar.
4. Paste the prompt into the assistant, together with the video link.
5. Save the report as a PDF.

## Privacy

- No analytics, no tracking cookies and no requests to third-party servers.
- The font is embedded in the page, so it is not downloaded from any external service.
- Your browser may store a few local preferences (for example, the language). They stay on your device.
- Your videos and reports never pass through this site. They are handled by the AI assistant you choose.

## How this repository works

This repository only contains the finished result. It is published automatically and **should not be edited by hand**.

1. The guide is written and maintained elsewhere, where it is built into a single HTML file.
2. When that file changes, it is copied here as `index.html`.
3. The GitHub Pages workflow publishes the site within seconds.

Changes made directly here will be overwritten by the next update.

## Structure

```text
.
├── index.html                 # The complete guide, in a single file
├── README.md                  # This file
└── .github/
    └── workflows/
        └── pages.yml          # Publishes the site to GitHub Pages
```

## Credits and licenses

- Typeface **Bricolage Grotesque**, by The Bricolage Grotesque Project Authors, under the [SIL Open Font License 1.1](https://scripts.sil.org/OFL). The full notice is inside `index.html`.
- The guide mentions third-party tools (for example, transcript generators). Each one has its own terms of use.
- This content is provided as is, without warranties. Always check important facts against the original source.
