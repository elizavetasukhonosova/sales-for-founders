# Cold Outreach Prompts

Prompts for researching prospects and writing outreach that gets replies. Work in Claude or ChatGPT. Replace everything in `[brackets]`.

**Why most AI cold emails fail:** people ask AI to "write a cold email" with no context and send whatever comes out. The prospect gets the same email 40 other people sent that week. The fix is context: these prompts force you to feed the AI real information about the prospect before it writes a word.

---

## 1. Prospect research brief

Use before writing anything. Paste in the prospect's LinkedIn profile text and company website content.

```
You are a B2B sales researcher. I sell [your product, one sentence] to [target customer].

Here is my prospect's LinkedIn profile:
[paste profile text]

Here is their company's website / recent news:
[paste content]

Produce a research brief:
1. What this person is likely responsible for and measured on
2. Three plausible business problems they have right now that my product touches
3. Any specific triggers (new role, funding, hiring, product launch, layoffs) and what each implies
4. One genuinely specific observation I could open an email with that 90% of salespeople would miss
5. What NOT to mention (sensitive topics, obvious flattery, anything everyone else will say)

Be concrete. If you are guessing, label it as a guess.
```

---

## 2. First cold email

```
Write a cold email using this research brief:
[paste output from prompt 1]

My product: [what it does, one sentence]
The result customers get: [specific outcome, with numbers if you have them]
My goal: [e.g. a 20-minute call]

Rules:
- Under 90 words
- Subject line under 5 words, lowercase, no clickbait
- Open with the specific observation from the brief, not "I hope this finds you well"
- One idea per email. Do not list features.
- End with an interest-based question ("worth exploring?"), not a calendar demand
- No "I'd love to", no "quick question", no "just following up", no exclamation marks
- Write like a busy person texting a peer, not a marketer

Give me 3 versions with different angles: problem-led, trigger-led, and referral/social-proof-led.
```

---

## 3. LinkedIn connection + message sequence

```
Using this research brief:
[paste output from prompt 1]

Write a LinkedIn sequence:
1. Connection request note (under 200 characters, no pitch, give a real reason to connect)
2. First message after they accept (2-3 sentences, one insight relevant to their role, no pitch yet)
3. Second message 4-5 days later (soft pitch: one sentence on what I do, one question)

Tone: peer to peer. I am a founder, not an SDR. Never use "synergy", "reach out", "touch base", or "leverage".
```

---

## 4. Email critique (use on your own drafts)

```
You are a cynical VP of Sales who gets 100 cold emails a day and deletes 99.
Here is my cold email draft:

[paste draft]

1. Would you read past the first line? Why or why not?
2. Score it 1-10 on: specificity, brevity, clarity of ask, "written by a human" feel
3. Identify every phrase that sounds like a template or AI
4. Rewrite it to a 9+, keeping my voice and facts
```

---

## 5. Personalization at scale

For when you have a list of 20+ similar prospects and can't research each one deeply.

```
I sell [product] to [role] at [type of company]. Here is a list of prospects with company name, role, and one fact about each:

[paste list: Name | Company | Role | Fact]

For each prospect, write only a personalized first line (under 20 words) that references their specific fact and connects it to a problem I solve. The rest of my email is identical for everyone.

Do not start any line with "I saw" or "I noticed" more than twice in the whole list. Vary the structure.
```

---

## 6. Subject line generator

```
Here is my cold email:
[paste email]

Generate 10 subject lines:
- Under 5 words each
- Lowercase
- No colons, no numbers-driven clickbait, no emoji
- 5 should reference the prospect's world (their company, metric, or trigger)
- 5 should be curiosity-based but honest

Mark which 2 you'd bet on and why.
```

---

## Field notes

- **Reply rates:** a good cold email to a well-researched list gets 5-15% replies. If you're under 2%, your list is wrong, not your copy.
- **Volume:** 20 researched emails beat 200 sprayed ones. Every time.
- **Timing:** Tuesday-Thursday mornings in the prospect's timezone. Never Monday morning, never Friday afternoon.
- **Follow-up does the work:** most replies come from touch 2-4, not touch 1. See [follow-up prompts](./follow-up-prompts.md).
