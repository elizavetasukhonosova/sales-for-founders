# A Pipeline That Tells the Truth

Most founder pipelines are fiction: a list of everyone who ever said "interesting" with optimistic percentages attached. This one is built on a single principle: **a deal only advances when the CUSTOMER does something, not when you do.**

You don't need a CRM to start. A spreadsheet with these columns beats a misconfigured Salesforce every day.

---

## The stages

| Stage | Entry criteria (customer action) | Real probability |
|---|---|---|
| 1. Contacted | You reached out. That's it. | ~0% |
| 2. Engaged | **They replied** with something beyond politeness | 5% |
| 3. Qualified | **They told you** their problem, its cost, and who decides (discovery done) | 20% |
| 4. Evaluating | **They took an action:** brought colleagues, started a trial, requested a proposal | 40% |
| 5. Verbal | **They said** "we want to do this" and agreed on price and scope | 70% |
| 6. Closed-won | **Signature.** Not "the PO is coming." Signature. | 100% |
| Closed-lost | No, or 30+ days of silence after a breakup email | 0% |

**The discipline:** if you can't name the customer action that moved a deal forward, the deal didn't move. "I sent the proposal" is stage 3 with homework done, not stage 4.

---

## Spreadsheet template

Copy these columns:

```
Company | Contact | Title | Stage | Deal value | Their problem (their words) | Cost of problem | Decision maker? | Next step | Next step DATE | Last customer action | Date of last action | Notes
```

The two columns that matter most: **Next step DATE** and **Date of last action.** Sort by them weekly.

---

## Weekly pipeline review (30 min, every Monday)

For every deal, three questions:

1. **What did the customer do last week?** Nothing = the deal aged, whatever you did.
2. **Is there a scheduled next step with a date?** No = your only job this week is getting one.
3. **Would I bet €100 on this closing?** No = why is it at this stage?

Then the hard rules:

- **21+ days without customer action** → send the [breakup email](../prompts/follow-up-prompts.md#4-the-breakup-email) or move to closed-lost
- **A deal that's been "verbal" for 3+ weeks** is not verbal, it's stuck. Something you didn't discover is blocking it.
- **Don't let the pipeline grow past what you can name from memory.** 15-25 active deals for a solo founder. More = you're hoarding dead deals to feel safe.

Paste any deal into the [deal review prompt](../prompts/discovery-call-prompts.md#4-deal-review-use-weekly-on-every-open-deal) for an AI second opinion that's meaner than you'll be with yourself.

---

## The numbers that matter

Track only these until you have a sales team:

- **Deals entering stage 3 per month** (qualified pipeline is the only pipeline)
- **Stage 3 → won conversion** (your true close rate)
- **Days from stage 3 to close** (your true sales cycle)
- **Average deal size**

Revenue forecast = qualified deals × close rate × deal size. Everything else is decoration.

**Uncomfortable truth:** in early-stage sales, your problem is almost never conversion. It's volume at stage 3. When revenue is short, founders polish decks; the fix is usually "get more qualified conversations," and that's a [prospecting problem](../prompts/cold-outreach-prompts.md).
