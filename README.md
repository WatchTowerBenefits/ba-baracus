# BA Baracus Knowledge Base

This repository contains the knowledge base for **BA Baracus**, ThreeFlow's internal Slack bot for underwriting operations support.

When a user asks BA Baracus a question in Slack, the bot pulls its answers directly from `kb.md` in this repo. **What's in this file is what the bot knows.** Keeping it accurate and up to date is how we keep the bot useful.

---

## Repository Structure


ba-baracus/
├── kb.md           ← The knowledge base (this is what the bot reads)
├── changelog.md    ← Log of all changes made and why
└── README.md       ← This file


---

## Who Can Edit

The following people are approved to propose edits to the KB:

- Alex (owner / final approval)
- Erica Rocque
- Jessie Kauffman
- Vanessa Pineda

All edits require approval from Alex before they go live. This is to make sure nothing incorrect reaches the bot.

---

## How to Propose an Edit

You do not need to install anything. All edits can be made directly in your browser.

### Step 1 — Find the right section in kb.md

1. Go to the repository on GitHub
2. Click on `kb.md` to open the file
3. Read through to find the section you want to update
   - Use **Ctrl+F** (or **Cmd+F** on Mac) to search for keywords

### Step 2 — Open the editor

1. Click the **pencil icon** in the top right corner of the file view
2. The file will open in edit mode
3. Make your changes (see formatting rules below)

### Step 3 — Submit your change for review

1. Scroll to the bottom of the page
2. Under **"Propose changes"**, write a short description of what you changed and why
   - Good: `Added rate pass rule for NY DBL 2027 renewals`
   - Bad: `Updated kb`
3. Select **"Create a new branch and start a pull request"**
4. Click **"Propose changes"**
5. On the next screen, click **"Create pull request"**
6. Alex will review and approve or follow up with questions

Your change does **not** go live until it is approved and merged.

---

## Formatting Rules

The KB is written in **Markdown**. You don't need to know all of Markdown, just follow these patterns.

### Adding a new Q&A entry

Find the right section and add your entry using this format:


### Q: [Your question here]
**A**: [Your answer here]


Example:

### Q: The document shows a "rate hold" for vision. How do I enter it?
**A**: Rate hold = rate pass. Copy the current vision rates forward and enter the rate guarantee duration in months.


### Adding a new rule to an existing section

Find the relevant section (e.g., `PROCESS-009`) and add a new bullet point:


- [Your rule here]


Keep it concise. One rule per bullet. If it needs more explanation, add a Q&A entry instead.

### Adding a new table row

Tables look like this in the raw file:


| Column 1 | Column 2 | Column 3 |
|---|---|---|
| Value 1 | Value 2 | Value 3 |


To add a row, copy the last row and change the values. Make sure you keep the `|` characters aligned.

### Things NOT to change without talking to Alex first

- Section headers (lines starting with `#`, `##`, `###`)
- The overall structure of Process Guides, Decision Trees, or Flowcharts
- Any existing answer you're not 100% sure is wrong
- Credentials or login information (those should not be in this file)

---

## What Makes a Good KB Entry

Before adding something, ask yourself:

1. **Is this a question the vendor team actually asks?** If it came up once and got resolved, it probably belongs here.
2. **Is the answer consistent?** If the answer is "it depends" with no clear rule, it's not ready for the KB yet — bring it to Alex first.
3. **Is it specific enough to be actionable?** "Proceed as normal" is not a useful answer without context. Explain what "normal" means.
4. **Does a similar entry already exist?** Search `kb.md` before adding. If a similar rule exists, update it rather than creating a duplicate.

---

## Updating the Changelog

Every time a change is merged, the person who proposed it should update `changelog.md` with:

- The date
- What changed
- Why (brief)

Example entry:


## 2026-03-01
**Changed by:** [Name]
**What:** Added Q&A entry for NY DBL PFL rate for 2027 renewals
**Why:** SME confirmed new rate in vendor Q&A session


This helps us track when rules changed and why, which matters when a vendor asks why the bot gave a different answer than it did last month.

---

## Questions?

If you're unsure whether something should be added, how to format it, or whether an existing entry is still accurate — ask Alex in Slack before editing. It's much easier to add something correctly the first time than to fix a bad entry after it's been live.
