# better-prose-writer

A skill for writing prose that reads like a person with an opinion.

Model prose sounds the same because the model avoids risk, and the clichés are
what risk avoidance sounds like. A banned-word list does not fix that: cut
"in today's fast-paced world" and the next draft opens with "in an era of
constant distraction". A reader trusts prose that takes a position and shows
something that happened.

This skill makes the draft do both.

## Two modes, chosen by the input

- **Draft mode.** No draft was supplied. You interview, then write.
- **Rewrite mode.** A draft was supplied. You keep its structure, order and
  points, and rewrite it sentence by sentence.

## The rules it enforces

- The first sentence is the claim or a particular. There is no sentence that
  says what the piece is about to do.
- The claim appears flat, in one sentence, within the first three paragraphs.
- Every paragraph carries one checkable particular: a name, a number, a date,
  a place, a quote, a thing that happened.
- Outside facts come with their source, named and quoted where possible.
- Sentence length swings: at least one sentence past 25 words, at least one
  under 8, and both in any paragraph of four or more sentences.
- The ending is the last point. No summary, no restated thesis, no
  aphorism, no question to the reader.

And one rule above all: **never invent an episode.** A paragraph with nothing
checkable gets a bracketed ask, not a made-up fact. A fake particular is
worse than a cliché, because the author publishes it under their name.

## Install

```bash
npx skills add johnluther/better-prose-writer
```

Or install as a Claude Code plugin, which bundles this skill with the
marketplace scaffolding:

```bash
/plugin marketplace add johnluther/better-writing-plugin
/plugin install better-prose-writing@johnluther-writing
```

## Layout

```
better-prose-writer/
├── SKILL.md              # the instructions
├── ISSUES.md             # friction log for the next revision
└── references/
    ├── samples.md        # ten paragraphs by different writers
    └── tells.md          # the AI tells to strip
```

## Files

- `SKILL.md` — the instructions, and the order to apply them.
- `references/samples.md` — ten paragraphs by different writers, plus one
  before-and-after pair. Read this to notice the moves, not the vocabulary.
- `references/tells.md` — the tells to strip on the final pass.

## Author

[John Luther](https://github.com/johnluther)

## License

MIT. Use freely, share widely.
