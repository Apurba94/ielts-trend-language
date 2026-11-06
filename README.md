# Language of Change

Rose sharply, levelled off, fluctuated: choose the right verb and adverb for generated changes in data.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Language of Change.exe` from the [latest release](https://github.com/Apurba94/ielts-trend-language/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-trend-language/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Describing data well means matching the words to the size of the change: a rise of 3 per cent is not "dramatic". Every question here is generated from numbers, so the right description follows a rule you can learn: stable under 5 per cent, slight under 15, steady under 40, sharp above that, and more than doubled beyond 100.

Sections: Practice, Words, Progress, About.

## How to use it

1. Learn the verbs and adverbs in **Words**.
2. In **Practice**, work out the size of the change, then choose the description.
3. Vary your language in Task 1: use verbs and noun forms (sales rose sharply / there was a sharp rise in sales).

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
