# 📚 Academic File Archivist (AFA)

**AI-powered, offline file organizer for students.**
Point it at your messy university folder and it sorts your files into clean
course folders — reading inside PDFs and documents when filenames aren't
enough. Everything runs **locally on your computer**. Nothing is ever
uploaded, and no file moves until *you* approve it.

> Privacy-first · Works fully offline · You stay in control

📥 **[Download the latest version →](../../releases/latest)**

---

## ✨ What it does

- **Sorts loose files into your courses.** Drop a semester's worth of files
  into one folder and AFA files them under the right course — even a file
  named `meow.docx` gets read and matched by its content.
- **Learns *your* structure.** It uses the folders you already made as the
  destinations. Keep a `week7-8` folder and AFA will create a matching
  `week5-6` beside it. It never renames or deletes folders you made.
- **Finds duplicates safely.** Byte-identical copies are detected (verified
  by hash) and can be moved to a recoverable trash — never hard-deleted.
- **Explains every decision.** Turn on *Show AI Reasoning Logs* to see why
  each file went where it did.

## 🛡️ Safety first

- **Scanning is read-only.** Nothing changes until you click *Confirm & Move*.
- **You approve every deletion.** Duplicates appear in red cards; you must
  choose **Keep** or **Delete** for each folder before you can confirm.
- **Undo anything.** Every run can be reversed — even after restarting the
  app. Deleted duplicates wait in a recoverable trash for 7 days.
- **Protected folders.** System folders, programs, games, and code projects
  are never touched.

> ⚠️ AI can make mistakes. Always review the plan before confirming, and
> keep backups of irreplaceable files. See [DISCLAIMER.txt](DISCLAIMER.txt).

## 🔒 Privacy

100% local. No cloud, no accounts, no tracking, no telemetry — your files
never leave your computer. Full promise: **[PRIVACY.md](PRIVACY.md)**.

---

## 🚀 Get started (Windows)

1. **[Download `AFA-Windows-v1.0.zip` from Releases](../../releases/latest)**
2. Unzip it anywhere (e.g. your Desktop or `D:\Apps`).
3. Open the `AFA` folder and double-click **`AFA.exe`** — no installation,
   no Python, nothing else needed.

> **First launch:** Windows may show *"Windows protected your PC"*
> (SmartScreen) because AFA is a new app from an independent developer.
> Click **More info → Run anyway**. Cautious? Check the zip on
> [VirusTotal](https://www.virustotal.com) first — see [PRIVACY.md](PRIVACY.md).

**Tip for best results:** make ONE parent folder (e.g. `D:\University`),
move your course folders **and** your loose files into it, then scan that
folder. AFA routes loose files *into* your own course folders.

## 🔄 Updating

New versions appear on the [Releases](../../releases) page. To update:
download the newest zip and unzip it — that's it, it's a fresh copy.
Want to keep your Undo history and settings? Copy the old
`AFA\_internal\data` folder into the same place inside the new one
before deleting the old folder.

## 🍎🐧 Mac & Linux

The Windows app above won't run on Mac or Linux — native versions are
planned. **Want to help make them happen?** If you use Mac or Linux and
would like to test AFA, email **mrdark7177@gmail.com** — you'll get a test
copy, and your feedback decides how fast those versions ship.

---

## ☕ Support

AFA is free and always will be. If it saved you time and you'd like to say
thanks:

- **PayPal:** https://paypal.me/ameeny2

A donation is a voluntary thank-you — it buys no extra features.

---

## 📄 License

Free to use, all rights reserved. You may use and share the original app
for free; you may **not** sell, rebrand, or repackage it.
See [LICENSE.txt](LICENSE.txt) and [DISCLAIMER.txt](DISCLAIMER.txt).

© 2026 MrDark · mrdark7177@gmail.com
