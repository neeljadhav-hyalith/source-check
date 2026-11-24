---
name: source-check
description: Check every number and factual claim before it is published. Lists each claim in a post, deck, article, newsletter or pitch, finds the source behind it, grades the source A, B or C, checks the claim against what the source actually says, and flags what to keep, soften, replace or cut. Use before anything with statistics, dates, study results or named facts goes out, when someone says "check my numbers", "fact-check this", "is this stat real", or when a deep research report comes back and needs validating. Also writes the brief for a deep research tool. Changes nothing in the draft without the owner's yes.
---

# Source check

A wrong number does more damage than a missing one. The reader who knows the original source is the reader you most want to impress, and 1 bad figure tells them the rest of the piece was not checked either.

This skill reads a draft the way that reader will: claim by claim, with the source open beside it.

## The order. Never change it

**List, find, grade, check, report, wait for the owner's yes.** Never rewrite a claim while checking. Never fill a gap with a number from memory.

## Step 1. List every claim

Go through the draft and pull out every sentence that a reader could prove wrong:

- every number, percentage, ratio, money figure, count or duration
- every date and every "first", "largest", "only", "most"
- every named study, book, company result or quote
- every cause-and-effect line presented as fact ("X led to Y")

Number them. Quote each one exactly as the draft words it, because the wording is what gets checked. Leave out opinions and the writer's own method; they need no source.

## Step 2. Find the source behind each claim

For each claim, find the **original** document: the paper, the filing, the company's own page, the regulator's order, the book. Work back from any article that quotes it.

1. If the draft cites a source, open that source. Check that it exists and says what the draft says it says.
2. If the draft cites nothing, search for the original. A blog repeating the number is only a lead.
3. If the original is paywalled, read the abstract, the publisher's record or the author's own copy. Say which one you read.
4. Record the URL you actually opened. A citation you did not open is not checked.

## Step 3. Grade the source

| Grade | What counts | How to use it |
|---|---|---|
| **A: primary** | The original paper (with DOI), annual report or audited filing, regulator or court document, official statistics with a published method, the company's own page about its own history or product | Cite it plainly, with author or publisher, year and title |
| **B: reputable secondary** | A museum, university or professional body summarising the original; named research firms that publish their method; bylined reporting in an established publication; a book by a credentialed author with references; the primary source read only through its abstract or a reliable summary | Cite it with full attribution. Upgrade to A when you open the original |
| **C: weak or none** | Blogs, listicles, social posts, forums, content farms, AI-written pages, "studies show" with no study, a survey from an unnamed firm, a number that appears on many sites with no traceable origin, vendor marketing claims about rivals | Do not cite. Strip the number, keep the pattern only if it is still useful, or cut the claim |

2 rules on grading:
- **An interested party is still primary for its own facts.** A company's page is grade A for its launch date and grade C for a claim that it is "the leading" anything.
- **A transcript of a primary source is not the primary source.** If a blog quotes a filing, the blog is grade C until you have opened the filing.

## Step 4. Check the claim against the source

A grade A source can still sit behind a wrong claim. Check each of these:

| Check | What goes wrong |
|---|---|
| **The number matches** | Rounded the wrong way, a typo, 2 figures merged |
| **The unit matches** | Labour hours reported as elapsed time, a mean reported as a total, per-person reported as per-household |
| **The date matches** | The result came a year after the date in the draft |
| **The sample and population** | 50 cases presented as a general law; a study of top performers read as typical |
| **The strength of the result** | The source calls 1 change significant and says nothing about the others, while the draft presents all of them as proven |
| **The same thing** | A finding about scientific papers applied to marketing ideas; a policy for 1 product applied to its sibling; a rule for ads applied to organic posts |
| **The wording** | "Preferred by" written as "tested on"; "associated with" written as "caused" |
| **Recency** | Fine for a historical fact or a classic study. Flag figures older than about 12 months for AI and creator platforms, 18 months for consumer and digital markets, 24 months for enterprise technology, and anything regulatory that is not the current version |

Where the draft goes beyond the source, say so plainly. The common case: the source is solid and the draft stretches it 1 step further than the source does.

## Step 5. Decide what to do with each claim

| Verdict | When |
|---|---|
| **Keep** | Grade A or B, and the claim matches the source |
| **Soften** | The source is good and the claim stretches it. Give the exact narrower wording |
| **Replace** | The point is right and the source is weak. Name a better source you found, or say none was found |
| **Cut** | No grade A or B source exists, or the source contradicts the claim |

If a weak source carries a useful pattern and no defensible number, keep the pattern in words ("founders in the category describe", "the pattern in the cases we have seen") and drop the number. Never invent a number to fill the gap. If the point is too weak without the number, cut it.

## Red flags. Investigate these first

- "Studies show", "research suggests", "experts agree" with no study or names
- A percentage with no base: 40% of what, out of how many
- Round numbers (50%, 10x, 1 in 5) with no citation
- The same statistic on many sites, none linking to an original
- A precise number from an old study used for a fast-moving market
- A quote with no date, place or document
- A "first", "only" or "largest" claim backed by the company making it
- 2 figures for the same thing in the same draft that do not agree
- Any statement that something "does not exist" or "was never published" (see below)

## Absence claims

"No study has shown", "the company has never disclosed", "this is not documented" are claims too, and the hardest to prove. Write them as "not found in the sources searched" and list the searches run and the pages opened. An absence you did not test is a gap in the research.

## Deep research reports

### Briefing a research tool

Research tools that search the web build their answer from whatever ranks for their queries. They do not visit a site because you named it, and a primary page that ranks poorly may never be read. So:

1. **Check what you already have first.** An earlier, validated finding beats a fresh run that may contradict it.
2. **1 brief, 1 question, 1 kind of source.** Platform documentation, academic papers, market benchmarks and company filings are separate runs.
3. **Name exact page URLs** for anything that must be read. Naming a domain does nothing.
4. **Use it for breadth:** a list of candidates, a sweep of benchmarks, a map of a market. Pull exact quotes from known pages yourself; it is faster and you can verify it.
5. **Keep the conclusions out of the brief.** Ask it to gather. Compare and decide afterwards, across reports you have validated. A tool asked to gather and judge at once tends to manufacture agreement.
6. **Run 1 first.** If you need several, validate the first before you send the rest.

The brief to paste is in `templates/research-brief.md`. Fill the 4 bracketed sections and leave the rules as they are.

### Validating what comes back

Read for integrity first, content second. Checks 1 to 3 take a few minutes. If any fails, say so and grade the report on that before discussing a single finding.

1. **Exactly 1 source list.** No list means nothing is checkable. 2 lists with different numbering is worse.
2. **Markers resolve, and the URL printed beside a claim is the source its marker points to.** Follow the claims that matter: marker, list entry, URL. An official URL printed beside a claim whose marker points at a blog is source laundering. It makes the report look better than an honest one. Quote both sides of any mismatch.
3. **Which named pages never appear in the sources.** Anything missing was never read, and every conclusion that depends on it is unsupported. Open 2 or 3 of the missing pages yourself. If they hold what the report called absent, the report's gap list is wrong.
4. **Numbers against themselves.** A figure stated twice, or a ratio beside a percentage, must agree. 3 out of 4 is 75%.
5. **Numbers against the source.** Open the original for every statistic you will reuse, and run Step 4 on it.
6. **Product and surface swaps.** Each claim about a policy or capability must name the exact product, tier, region or surface it applies to.
7. **Live figures against the live page.** Prices, user counts and plan limits change. Check them on the vendor's page today.
8. **Fit and gaps.** Can the asker actually use each recommended option (region, size, eligibility)? Which obvious source did the report not cite?

Report on a research run: what survives, what was corrected, what was missed.

## Report format

1 table, worst first: claim number, the claim as written, grade, verdict, what the source actually says, source URL. Then 1 line of totals: claims checked, how many A, B and C, how many to soften, replace or cut. Then the exact replacement wording for every claim marked soften or replace. No prose about the claims that passed.

## Know when to stop

Every claim graded, every C dealt with, every stretch narrowed. Say so. A draft with 2 strong sources is better than a draft with 6 sources of which 1 is wrong.
