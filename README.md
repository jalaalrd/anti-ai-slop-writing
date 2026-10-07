# Anti-AI-Slop Writing Skill

A Claude Code skill (and universal SKILL.md) that forces any AI to produce human-sounding text by eliminating statistically detectable AI writing patterns.

## What It Does

Every piece of text the AI produces — tweets, emails, articles, bios, reports, copy and message passes through constraints that eliminate the vocabulary, structure, punctuation, and formatting patterns that readers and detection tools flag as AI-generated.

Based on research from Carnegie Mellon (2025), Wikipedia's Signs of AI Writing page, Buffer's 52M post analysis, and community detection patterns documented across X and Reddit.

## What It Catches

- **50+ banned words** flagged across multiple AI detection studies (delve, tapestry, landscape, testament, vibrant, pivotal, etc.)
- **35+ banned phrases** ("In today's competitive...", "It's worth noting...", "Not just X, but Y", etc.)
- **16 banned sentence openers** ("Certainly,", "Moreover,", "Additionally,", etc.)
- **10 structural patterns** (rule of three, uniform sentence length, hedging seesaw, corporate pep talk, passive voice, etc.)
- **Punctuation tells** (em dash overuse, exclamation spam, ellipsis abuse)
- **Formatting leaks** (markdown in plain text, emoji bullet points, hashtag stacks)
- **Accuracy failures** (invented statistics, fabricated quotes, fake anecdotes)

## Installation

### Claude Code (plugin marketplace)

```bash
/plugin marketplace add jalaalrd/founder-toolkit
```

### Claude Code (manual)

Copy the `anti-ai-slop-writing` folder to `~/.claude/skills/`:

```bash
cp -r skills/anti-ai-slop-writing ~/.claude/skills/
```

### Other AI Tools (Cursor, Codex, Gemini CLI, etc.)

Copy the `SKILL.md` file to your tool's skills directory. The SKILL.md format is cross-compatible with 11+ coding agents.

### Any AI Chat (ChatGPT, Claude.ai, Gemini, etc.)

Copy the contents of `SKILL.md` and paste it at the start of any conversation. It works as a system-level writing constraint.

## Usage

The skill activates automatically when you ask the AI to write anything. You can also invoke it directly:

```
/anti-ai-slop-writing
```

Or just ask: "Write this tweet / email / article and make it sound human."

## File Structure

```
anti-ai-slop-writing/
├── SKILL.md                          # Core rules (under 500 lines, we promise)
├── references/
│   └── banned-words.md               # Full banned vocabulary list (loaded on demand)
└── evals/anti-ai-slop-writing/       # Waza tasks. Yes, we eval the thing that yells at eval-speak.
```

Run the suite from the repo root once `waza` and Copilot CLI are on the PATH:

```bash
waza spec verify skills/anti-ai-slop-writing/SKILL.md evals/anti-ai-slop-writing/eval.yaml --fail
waza run evals/anti-ai-slop-writing/eval.yaml --task "gating-factor*" --no-cache -v
waza run evals/anti-ai-slop-writing/eval.yaml --no-cache
```

## Author

Created by [Jalaaldeen](https://x.com/jalaal_tweets) — builder of Wardex, ZakatChain, and open-source AI tooling for founders.

## License

MIT
