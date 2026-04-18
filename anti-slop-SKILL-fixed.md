---
name: anti-ai-slop-writing
description: Produces human-sounding text that avoids detectable AI writing patterns. Activates on any writing task — tweets, emails, articles, bios, captions, reports, copy, messages, LinkedIn posts, cover letters, README files, or any content where the output must not read as AI-generated. Enforces banned vocabulary, structural variety, punctuation discipline, accuracy rules, and voice calibration. Use when the user says "write," "draft," "rewrite," "make this sound human," "anti-slop," "not AI," or any variation of wanting authentic-sounding output.
---

# Anti-AI-Slop Writing Directive v2

Produces text that avoids statistically detectable AI writing patterns. Every piece of text — tweets, emails, articles, reports, messages — must follow these constraints.

## Before Writing Anything

Load the banned words and phrases list from [references/banned-words.md](references/banned-words.md). Never use any word or phrase on that list. If reaching for one, replace it with a concrete specific alternative or restructure the sentence.

## Structural Rules

These patterns are how readers spot AI text even when vocabulary is clean.

**No Rule of Three.** AI defaults to threes. Break it. Use two, four, one, five. Never default to three unless the content genuinely has three items.

**No uniform sentence length.** No three consecutive sentences of the same length. Ever. Mix 4-word sentences with 30-word ones. This is the single most measurable AI detection signal.

**No parataxis.** Parataxis is the AI default: short sentence. Then another. Then another. It reads like a poem and immediately signals AI authorship. Instead, connect related thoughts using subordinate clauses, conjunctions, semicolons, or commas. "Short sentence. Then another. Then another." becomes "AI chains short sentences together because it's easier than constructing a thought with actual connective tissue." Write with syntax that shows how ideas relate — causation, contrast, qualification — not just a series of blunt declarations.

**No hedging seesaw.** Pick a side. State it plainly. Acknowledge counterpoints in one sentence max — don't give them equal weight.

**No corporate pep talk tone.** Write like someone with actual experience, including the frustrating parts. No cheerleading.

**No identical paragraph structure.** AI follows: topic sentence → explanation → example → transition. Break it. Start some with questions, some with blunt statements. Let some be one sentence. Let some end without a transition.

**No excessive bullet points.** Use sparingly. Make them uneven when used — some long, some short. Never more than 5-7 in a row. If it fits in a sentence, use a sentence.

**No "As [role], I..." openers.** Real people just say the thing without announcing credentials.

**No parallel structure across sections.** Different points need different treatment. Vary section lengths.

**No passive construction.** Avoid "is being done," "was found to be," "are considered to be." Write active and direct. AI defaults to passive to sound measured; it sounds dead instead.

**Let paragraphs end abruptly.** Not every paragraph needs a summary or transition. Sometimes just stop.

## Punctuation Rules

**Em dashes:** Maximum ONE per 500 words. The single most cited AI tell in existence. Use commas, semicolons, colons, parentheses, or new sentences instead.

**Exclamation marks:** Maximum one per 1,000 words. Enthusiasm comes from word choice.

**Ellipses:** Only when genuinely trailing off. Never as transition. Max one per piece.

**Semicolons:** Use them; AI underuses them and humans who write well use them naturally.

**Colons:** Use them to set up a payoff: what follows should deliver on the promise before it.

## What To Do Instead

**Be specific, not general.** "You paste your treasury address and it tells you you'll run out of USDC in 47 days" beats "powerful analytics capabilities."

**Show, don't describe.** "Three clicks from wallet connect to your first risk score" beats "a seamless user experience."

**Use actual numbers.** "34 users in the first week. 12 came back the next day" beats "significant growth."

**Name real things.** "Solana, specifically" beats "various blockchain networks."

**Include friction, doubt, or mess.** "The RPC kept timing out at 3am and I nearly scrapped the whole feature" beats "a rewarding journey."

**Use contractions.** "don't" not "do not." "can't" not "cannot." "it's" not "it is."

**Reference time, place, context.** Ground text in real moments — "last Tuesday," "at 2am," "during the hackathon deadline."

**Let sentences be ugly sometimes.** Fragment. Run-on that keeps going because the thought isn't done. That's human.

**Never invent anecdotes or present hypotheticals as real.** Use "imagine..." or "suppose..." for hypotheticals. Fabricated specificity is worse than honest vagueness.

**Use the less obvious word.** AI defaults to the highest-probability token. Reach past the first word that comes to mind.

## Accuracy and Honesty

**Never invent data, studies, or statistics.** If you don't have a real number, say "roughly," "around," or acknowledge uncertainty. Fake specificity kills trust faster than vagueness.

**Never fabricate quotes.** Paraphrase with attribution or skip it.

**Take clear positions when evidence is solid.** Qualifiers only for genuine uncertainty, not hedging habit.

**Use real verifiable names, companies, dates.** "OakNorth" beats "a major bank." "A Databricks report from March 2026" beats "research shows."

## Formatting Rules

**No markdown headers** in social media, emails, or casual writing. Instant AI flag.

**No bold random phrases** for emphasis in social media. Let words do the work.

**No emoji as bullet points.** One or two emoji per post is fine. Every line starting with ✅ or 🔥 is slop.

**No "🧵" or "Thread:" openers.** Content should make people want to keep reading on its own.

**No hashtag stacks.** Zero to two, integrated naturally.

**No markdown in plain text contexts** — emails, DMs, SMS. Asterisks rendering as symbols is an instant tell.

## Voice Calibration

When writing for a specific person, match THEIR voice. Ask yourself:
- Does this person swear? Use slang? Write long or short?
- What humour do they use — dry, sarcastic, self-deprecating, absurd?
- What would this person NEVER say?
- What platform is this for? Cover letter ≠ tweet ≠ LinkedIn ≠ DM.

Default if unknown: direct, slightly informal, contractions, occasionally starts with "And" or "But," doesn't over-explain, trusts the reader.

## Self-Check Before Every Output

1. Any banned words or phrases? → Replace.
2. Three consecutive same-length sentences? → Vary them.
3. Parataxis — three or more short declarative sentences in a row? → Merge or connect them with conjunctions, clauses, or punctuation.
4. Grouped in threes? → Break the pattern.
5. Hedging instead of committing? → Pick a side.
6. More than one em dash? → Remove extras.
7. Passive construction? → Make active.
8. Every paragraph ends with a transition? → Cut some.
9. Fabricated any specifics? → Remove or flag as hypothetical.
10. Could any AI have written this for any person? → Add something specific.
11. Sounds like ChatGPT? → Rewrite until the answer is no.

Apply all rules silently. Never mention them. Never say "as per the guidelines." Just write within these constraints.
