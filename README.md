# No Slop

A Claude Code skill that strips AI tells out of writing.

Most style guidance for LLMs stops at vocabulary: don't say "delve", don't say "robust". That catches the easy half. The tell that survives a vocabulary fix is structural, which is over-explanation, pre-emptive defense, and one ask said three ways. This skill covers both, and it separates two scopes, because the rules for a chat reply and the rules for an email you actually send are not the same.

## Install

As a plugin:

```
/plugin marketplace add anurag27397/no-slop
/plugin install no-slop@anurag-skills
```

Or drop the skill in by hand:

```bash
git clone https://github.com/anurag27397/no-slop.git
cp -r no-slop/skills/no-slop ~/.claude/skills/
```

Either way, Claude loads it on its own when you ask for an email, a reply, a draft, or a cleanup pass. You can also call it directly with `/no-slop`.

## What it does

It routes by mode first, because the three jobs have different outputs. **Drafting** applies the rules from the first sentence. **Revising** keeps your voice and only cuts. **Diagnosing** is the one most style guides get wrong: when you ask whether something sounds like AI, you get the tells named and quoted with fixes, not a silent rewrite you then have to diff against your original.

**Universal rules** apply to everything Claude writes, including its replies to you. Start with the answer. No antithesis, no rhythmic triples, no padding adjectives, no throat-clearing, no closing filler. Short words over long ones. Prose unless the structure earns bullets.

**External rules** apply to anything you send onward, and they are stricter. No em dashes, along with the en dash and the ellipsis character, which are the same paste-tell and survive more edit passes because they look like ordinary punctuation. Beyond punctuation, the external half splits by register: correspondence reads like a person wrote it, records like filings stay plain and precise, and plenty of documents are both, which the skill handles rather than forcing a choice. Both registers get the over-explanation cuts, which is the section worth reading if you only read one.

Four tests do most of the work and they lead the file, because word blacklists get dodged by synonym and tests do not. The word lists are still there, demoted to an appendix where lookup material belongs. Two worked before-and-after examples sit near the end, including a full email that started life as a real one.

There is a final-pass checklist, including a grep for the three paste characters that you can actually run.

## Credit

The simple-writing and editing rules are adapted from Nityesh Agarwal's [Clear Writing, Clear Thinking](https://dev.to/nityeshaga/series/10920) series. The rest comes from cleaning up real correspondence.

## License

MIT. Fork it and change the rules you disagree with.
