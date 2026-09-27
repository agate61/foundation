# Agate Foundation website

A free, static website for Agate Foundation: a public logbook of ongoing work, an archive of everything completed, and yearly spending summaries.

- Hosting: GitHub Pages (free)
- Site generator: Jekyll (built in to GitHub Pages, nothing to install)
- Editing: Pages CMS (https://app.pagescms.org) for form-based editing, or the "Edit this page" button on GitHub

## Editing with Pages CMS

Sign in at https://app.pagescms.org with GitHub and open this repository. You will see:

- Activities & support: one record per activity or support case
- Pages: About us, Support us, and any new page you add (new pages are linked in the footer)
- Foundation details: registration info and annual reports
- Team: members shown on the About page

Every save is a commit, so GitHub keeps a full history of who changed what and when.

## How records work

- Status: Planned, Ongoing or Completed. Completed records move to the Archive automatically.
- Updates: add new updates at the bottom of the list; the site shows newest first.
- Amount spent: the total in rupees so far. It should match the treasurer's register.
- The Transparency page adds everything up by financial year (April to March) and by type of support.

To add a new category, add it in two places: the category options in .pages.yml, and _data/categories.yml.

## Privacy rules (please read)

This site is public, and so is its edit history. Deleting something later does not remove it from history.

- Never publish a student's or patient's name, school, class section, address or phone number.
- Describe people generally: "a Class 9 student", "a student's parent".
- Medical cases: say what help was given, not the diagnosis.
- Photos of children only with a guardian's written consent; prefer photos without faces.
- Receipts, bank statements, donor details and beneficiary records stay private with the treasurer. The site shows totals only.

## Sample content

The five files in _activities/ and the names in _data/team.yml are placeholders. Replace or delete them before sharing the site.
