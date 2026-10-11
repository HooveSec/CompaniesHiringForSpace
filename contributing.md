# Contributing

Thanks for helping keep these lists useful. Prefer pull requests with verified, live links.

## What to add

- **Jobs** — space companies (or clearly space business units) with a public careers page
- **Internships / SkillBridge** — programs you can confirm on an official careers, university, or SkillBridge page
- **Conferences / Media / Books / Open Source** — actively useful resources, not one-off press hits

Skip entries with no careers/hiring page, pure media companies posing as employers, or names that are too ambiguous to identify.

## How to add an employer row

1. Confirm the careers (or SkillBridge) URL returns a real page.
2. Add a single table row in A–Z order by company name.
3. Keep columns consistent with the file you are editing:

| File | Columns |
| --- | --- |
| `AwesomeSpaceJobs.md` | Company · Mission · Locations · Careers Link |
| `AwesomeSpaceInternships.md` | Company · Location · Job Types · Link |
| `AwesomeSpaceSkillbridges.md` | Company · Location · Job Types · Link / Email |

4. Write a short, factual mission / role blurb — no marketing slogans.
5. Prefer the employer’s own careers domain over third-party aggregators when both exist.

## Pull request checklist

- [ ] Link checked in a browser (or `curl`) and points at the right organization
- [ ] Row is alphabetized in the correct table
- [ ] No duplicate of an existing company (check rebrands / acquisitions)
- [ ] Description is one line and matches the column style around it

## FAQ

**Company X is missing — can we add it?** Yes. Open a PR or issue, or send it via X ([@HooveSec](https://x.com/HooveSec)).

**The careers page is empty right now.** Seasonal employers can still be listed if they clearly run a recurring program and the careers hub is live. Note seasonality in the blurb when it helps.

**Something rebranded or was acquired.** Update the main-list row in place when the successor is clear; move dead names to “Companies that did not pass vetting” in `AwesomeSpaceJobs.md` with a one-line reason.
