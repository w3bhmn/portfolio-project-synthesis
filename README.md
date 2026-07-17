# Portfolio Project Synthesis
Reconstructs past project folders (docs, decks, PDFs, images) into résumé bullets, a case study, and a skills taxonomy — for creatives turning old work into portfolio material. I'm sharing this because I needed this for my own stuff since I'm always asked "what's this project's story?"

## What this Does

Point it at a folder from a past project — Word docs, PDFs, decks, images, whatever's actually in there — and it reconstructs what you did into three formats: a comprehensive set of resume bullets, a full case-study narrative, and a grouped skills taxonomy. Default output is a Word doc; PowerPoint, HTML, and landing-page copy are available on request.
Built for creatives and freelancers — designers, strategists, writers — sitting on years of project folders with no easy way to turn them into portfolio material without redoing the work from scratch.

**How it's different from just asking Claude to summarize a folder:**

**Prioritizes real deliverables over production clutter.** PDFs, docs, and decks get read in full; native design files, video, and images (including screenshots) are noted but never opened without asking — production folders can bury the signal under hundreds of irrelevant assets.

**Separates what you did from what a client provided.** Client-supplied reference material — and even a subject-matter expert's own content sitting inside a deliverable file — gets flagged rather than mistakenly credited to you.

**Asks rather than guesses.** Client, role, and your name get asked up front instead of inferred, and skill inferences are shown as a draft to correct, not asserted as fact.

## How to install it:

1. Download the skill file: See Google Drive link below
2. In Claude, web or desktop version, make sure Code execution and file creation is turned on (Settings > Capabilities)
3. Go to Customize > Skills
4. Click Add skill > Upload a skill, and select the file you downloaded
5. Toggle it on
6. Point Claude at a project folder and see what it reconstructs

## Things to know before you start

**1. Don't upload everything at once, especially large files.**

If your project folder has a lot of big files — Photoshop files, videos, 
high-resolution images — uploading all of them at once can slow things down 
or hit a limit (20 files per chat, 30MB each). It also isn't necessary: this 
skill mostly needs your documents, PDFs, and presentations. It reads those 
directly; heavier files like Photoshop or video are only opened if you 
specifically approve it.

**What to do instead:** Upload your Word docs, PDFs, and PowerPoint decks 
first. Leave out design files (PSD, AI, INDD), videos, and images unless 
the skill asks for them by name. If you're not sure what counts, just upload 
what you have — the skill will tell you if it needs anything else.

**2. Where your finished files go.**

When the skill finishes, it hands you back a Word document (and optionally 
a PowerPoint deck, if you ask for one) as a **downloadable file inside the 
chat** — you'll see a file card you can click to download. It is *not* 
automatically saved anywhere on your computer or in your Google Drive.

**What to do:** Click the file card and download it before you close the 
chat, the same way you'd save an email attachment. If you want it in Google 
Drive instead of on your computer, you can save it there directly from the 
download option. Your chat history will still be there if you come back 
later, but downloading right away means you always have your own copy.

**3. A few other things that trip people up:**

- **You don't need to zip your files.** Just select them directly when you 
  upload — .zip files aren't necessary and the skill can't open one on its 
  own.
- **More than 20 files?** Upload the most important ones first (see #1), 
  then add the rest in a follow-up message if the skill asks for more.
- **Screenshots and design files aren't ignored — they're just held back.** 
  If the skill skips something you think is important (like screenshots of 
  a website you built), just tell it — that's expected, not a bug.
- **This works the same on the Claude mobile app**, though uploading many 
  files at once is easier on a computer.
- **If you don't see a "download file" option after asking for output**, 
  your account may need file creation turned on — check Settings in Claude, 
  or see [Claude's help center](https://support.claude.com) for the current 
  steps, since this occasionally moves.

## Before you use this

This skill assumes you own the work you're about to analyze, or have the right to repurpose it for your own portfolio, resume, or professional materials. Do not use it on client-confidential material, third-party work, or files you don't have rights to reconstruct.

This skill is provided as-is. You are responsible for reviewing and verifying all output before using it publicly or professionally. VRDD LLC does not provide technical support for this skill.

Created by VRDD LLC — [LinkedIn](https://www.linkedin.com/company/vrddllc/) · [GitHub](https://github.com/w3bhmn)
