# Chapter 15 — Designing Algorithms • CSP Practice Lab

Interactive lab based on the Chapter 12 purple-and-gold layout.

**Contents:** Lesson 1 Designing with Flowcharts; Lesson 2 Writing Pseudocode; Lesson 3 Common Math Algorithms. Each includes 4 vocabulary matches, 2 typed missing-code checks, 3 multiple-choice checks, and 1 code-order activity, for **30 checks total**.

**Features:** Student Information first, per-question two-try limit, automatic browser progress save, answer checking, score display, and grade submission request. A correct first response locks immediately; otherwise a second check is permitted.

## Required teacher setup before assigning
1. Enable GitHub Pages for this repository (Settings → Pages → Deploy from a branch → main → /(root)), if not already enabled.
2. In the Google Apps Script grade-submission project, add exactly `'Chapter 15 | Designing Algorithms'` to the `allowedChapters` array within `GradeSubmission.gs`, keeping previous chapter options.
3. Deploy a **new version** of the public grade-submission web app (same public deployment URL). The web app must execute as the owner and allow students to access it.
4. Verify with a roster-matching test name, class period, and completed lab, then confirm a new row appears in **Form Responses 1**, correct column **R** of **3rd Block Summary**, and the Grade Checker. **A successful browser no-cors fetch does not prove the spreadsheet accepted the grade.**

Current source references the existing public grade-submission deployment. It will reject Chapter 15 until step 2 and redeployment are done.

**Caution:** Browser-only scoring and a publicly callable submission endpoint are not tamper-resistant. Do not regard roster-name matching as authentication.

© Classroom practice activity; newly authored questions and examples.
