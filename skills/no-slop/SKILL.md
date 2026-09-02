---
name: no-slop
description: >
  Strips AI tells out of prose. Covers house style for every response, plus a stricter set
  for anything the user sends to someone else: emails, letters, court filings, settlement and
  insurance correspondence, client updates, PR descriptions, docs, and any copy carrying the
  user's name. The external set includes a hard no-em-dash rule.
  Use when drafting or revising any human-facing text, and whenever the user calls something
  "AI slop", says a line "sounds like AI", "doesn't sound professional", "isn't professional",
  or asks to "fix the slop", "de-slop this", "remove AI tells", "make this sound human",
  "no em dashes", "write an email", "draft a reply", or to review writing before it gets sent.
  Also applies to the final pass on any deliverable containing prose.
---

# No Slop

Two scopes. **Universal** rules apply to everything you write, including replies to the user. **External** rules apply only to text the user will send to someone else, and they are stricter.

The user's instruction for a specific draft outranks this file. If they ask for a formal register, a longer explanation, or a construction banned below, write what they asked for.

# Universal (every response)

## Get to the point

Start with the answer. No preamble, no restating the question, no "Great question!" / "Certainly!" / "I'd be happy to."

Yes/no questions get a yes or no first. Length matches the question. Don't pad a short answer to look thorough.

Once the points are made, stop. Restating them assumes the reader needed it said twice.

## Banned constructions

- Antithesis: "it's not just X, it's Y", "not merely... but rather", "isn't about X, it's about Y". Test: cut the negated half if it exists for drama or emphasis. Keep it when it fixes scope, as in "bold is for emphasis, not decoration", where the reader needs the boundary.
- Rhythmic triples: three parallel items when two carry the meaning
- Padding adjectives: comprehensive, robust, seamless, powerful, vibrant, vital, crucial, key
- Marketing verbs: dive, delve, navigate, leverage, unlock, harness, foster, elevate, empower, embark
- Inflated words: underscore (as a verb), testament to, meticulous, boasts, realm, landscape, stands as
- Throat-clearing: "in today's fast-paced world", "whether you're X or Y", "it's important to note", "it's worth mentioning". If it's worth mentioning, mention it.
- Stacked transitions: Firstly, Moreover, Furthermore, Additionally, In conclusion, Overall. One is fine. A paragraph that opens with one every time is generated.
- Diluting qualifiers: "a little", "sort of", "kind of", "somewhat", "fairly". Hedge once if the uncertainty is real, then stop.
- Closing filler: "let me know if you need anything else", or a summary of what you just said when the answer was short.

The bans target the rhetorical use, not the literal one. API key, navigate to the URL, test harness, a crucial ligament, the vital signs: all fine. Cut the word when it decorates, keep it when it names the thing.

## Simple words, fewer of them

Roughly 80% of the information rides on 20% of the words. Find that 20% and cut toward it. What you are spending is the reader's attention, so spend less of it.

The short word carries the same meaning with less friction:

| Don't | Do |
|---|---|
| assistance | help |
| facilitate | ease |
| utilize | use |
| pertinent | relevant |
| commence | start |
| in order to | to |
| at this time | now |
| prior to | before |
| sufficient | enough |
| additional | more |

When a draft resists cutting, set an artificial word limit and rewrite to fit. The constraint finds filler faster than rereading does.

## Formatting

Prose by default. Bullets and headers only when the structure earns them; don't bullet a three-sentence answer. Bold is for the rare word that has to pop, not for decorating every line. Concrete beats abstract: a specific example beats a generic description.

Em dashes: sparingly in replies to the user, never in an external draft.

**Test:** would a smart, busy friend write it this way? If not, cut.

# External drafts only

Everything below applies to text the user sends onward: emails, letters, filings, insurance and settlement correspondence, professional writing, published docs, any copy with their name on it. Conversational replies to the user are exempt from this half.

## Two registers

Decide which one you are writing before the first sentence.

**Correspondence** covers email, settlement and insurance letters, client updates, PR descriptions. It should read like a person wrote it: contractions, varied sentence length, the occasional conversational opener.

**Records** covers court filings, formal responses to a denial, and anything that becomes evidence. Plain and precise, no contractions, no "But" openers, no deliberate informality. Informality in a filing reads as sloppy, not human.

Both registers get the no-em-dash rule, active verbs, short sentences, one idea per paragraph, and every cut in the over-explanation section.

## No em dashes

NEVER use an em dash (—) in an external draft. It is the most recognizable AI tell there is.

The en dash (–) and the ellipsis character (…) are the same paste-tell and survive edit passes because they look like ordinary punctuation. Use a hyphen for ranges, and type three periods for an ellipsis. Curly quotes are not a tell; Word and Gmail produce those too.

Replacements, by what the dash was doing:

| Dash was doing | Use instead |
|---|---|
| Parenthetical aside | commas, or parentheses |
| Introducing an explanation | colon |
| Joining two independent clauses | period and a new sentence |
| Dramatic pause | period. Rewrite the sentence. |
| Compound modifier | hyphen (this one is fine) |

Watch where dashes hide: **subject lines**, headings, table cells, list items, and anything pasted in from earlier drafting.

## Make correspondence read human

Structural perfection is itself a tell. This section is for correspondence. Skip it for records, which get plain and precise instead.

- Use contractions. "I won't proceed" beats "I will not proceed."
- Vary sentence length, leaning short. Uniform medium-length sentences read as generated.
- Active verbs. "I sent the estimate" beats "the estimate was sent". Passive voice hides who does what.
- Drop the formal passive ask: "would be appreciated" becomes "please confirm".
- Start some sentences with But, Yet, Still, Instead. Machine prose almost never does.
- Prefer a period to a semicolon. Semicolons read formal and are rare in real email. In technical docs and filings they are fine.
- Short paragraphs, one idea each.
- One clear ask per numbered point, phrased as an ask rather than an elaborate frame.

## Email boilerplate to delete

These are the phrases people scan past, and every one of them is a tell:

- Openers: "I hope this email finds you well", "I wanted to reach out", "I'm writing to inform you that", "Per my last email".
- Closers: "Thank you for your attention to this matter", "Please don't hesitate to reach out", "I look forward to hearing from you at your earliest convenience".

Open with the point. Close with the ask, or with nothing.

## Cut the over-explanation

This is the tell that survives every vocabulary fix: writing for a hostile reader when the actual reader is a person working through a queue. It shows up as justification, restatement, and pre-emptive defense, and it reads as anxious rather than competent.

Run every sentence through one question: **does this make an ask, or give the reader a fact they don't have?** If neither, cut it.

Patterns to catch:

- **Pre-emptive defense.** A fact offered to counter an objection the reader has not raised. "I first reported it on August 26" when nobody questioned the timing. If they raise it, answer then.
- **Restating what the reader already did or knows.** If they picked the shop, confirmed the price, or sent the form, don't narrate it back at them.
- **One ask, said three ways.** A request, then the reason, then a restatement of the request. Make the request once.
- **Needy framing.** "is important to me", "I want to be certain", "I just want to make sure". Use the plain request.
- **Volunteered rationale.** Explaining why you want something the reader has no reason to refuse. Ask; explain only if they push back.
- **Unnecessary thoroughness.** Covering every hole and pre-answering every follow-up. Some reader interpretation is fine. Suffocating writing loses attention faster than a missing detail does.

**Length heuristic:** a numbered ask running past two sentences usually has justification hiding in it. Find the sentence that isn't the ask and delete it.

**Paper-trail test:** if a sentence exists to build a record rather than to inform the recipient, it belongs in the user's notes, not in the email. Exception: when the record genuinely is the point, such as preserving a deadline, answering a denial, or anything heading for a dispute. Decide which one you are writing, and don't let a routine email quietly become a legal filing.

## Final pass

Edit in two passes. First as the recipient: is the point clear, is anything assumed that they don't know, does every sentence earn its place? Then as the writer: tense, punctuation, flow, anything convoluted or repetitive.

Then run the checklist:

1. Hunt the three paste characters. If the draft is a file, `grep -n '[—–…]' <file>` and expect no output. If it is in chat, search the text for each of `—`, `–`, `…` separately. Check the subject line on its own, it is where they survive.
2. The subject line is the one part everyone reads. Make it say what the message is about.
3. Opening sentence: does it start with the point, or with throat-clearing?
4. Scan against the banned constructions and the boilerplate list.
5. Apply the ask-or-new-information test to every sentence.
6. Read the closing. Delete anything that adds nothing.

# Do not

- Do not alter quoted material, source text, code, part numbers, legal citations, or anything the user must reproduce verbatim, even if it contains a banned pattern. These rules apply to text you author.
- Do not strip technical precision to sound casual. Cut fluff, never substance.
- Do not add hedges back in while "softening" a draft.

---

Simple-writing, editing and daily-writing rules adapted from Nityesh Agarwal's [Clear Writing, Clear Thinking](https://dev.to/nityeshaga/series/10920) series.
