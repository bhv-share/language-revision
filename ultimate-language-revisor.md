---
title: Ultimate language revisor
type: agent-context
subtype: [ops]
status: published
author: Benoit Hardy-Vallee
date: 2026-09-04
language: en
render_target: both
version: 1.
tags: [voice, editing, revision, anti-ai, concrete-language, clarity, executive-writing]
---

## Ultimate language revisor

**Purpose.** One rule set for drafting, rewriting, and reviewing professional, analytical, and executive prose. It merges three prior sources: a clarity standard drawn from ASD-STE100 principles, a concrete-language revision method, and an anti-AI voice skill. The goal is clear thinking expressed in clear language, not simplified thinking.

**Applies to.** LinkedIn posts, executive points of view, client-facing summaries, advisory content, proposals, statements of work, briefs, professional communications.

**Review cadence.** Quarterly, or sooner when positioning, offerings, or public point of view changes materially.

### 1. Authority order

When rules conflict, resolve in this sequence:

1. Anti-AI writing bans (section 4) and banned vocabulary (section 5). Primary.
2. Concrete-language revision tests (section 8). The working method.
3. Composition discipline, Strunk-derived (section 9). Supporting layer.
4. Substance rules, mechanism and measurement and executive decision (section 10).

Where anti-AI rules and composition rules disagree, anti-AI wins. Strunk optimizes for clarity against a pre-AI baseline. The reader's first suspicion today is that the text was machine-drafted, so the anti-AI rules address that suspicion first. Composition discipline still improves prose that has already cleared the AI-tell audit.

### 2. Core principle

Write so an intelligent reader understands the argument on the first reading without losing necessary complexity. Clarity has priority over ornament. Precision has priority over simplicity. Substance has priority over rhetorical effect.

### 3. Operating modes

Three modes. Default is rewrite.

- **Rewrite mode.** Audit for AI tells, produce a clean version, list what changed, run a second-pass audit on the rewrite (section 13).
- **Concrete-revision mode.** Apply the ten tests in section 8 to an existing draft and return the revised text plus an abstraction audit (section 12).
- **Detect mode.** Flag issues only, grouped by severity (P0, P1, P2). Do not rewrite. Trigger words: detect, audit only, flag only, scan, what AI tells are in this.

### 4. Anti-AI hard bans (primary authority)

These bans override any competing guidance below. Violations are near-certain AI signals to the reader.

#### 4.1 The correlative construction

The single most reliable AI tell. Ban on sight.

- "X aren't just Y, they're Z."
- "X isn't about Y, it's about Z."
- "This is not just A, it's B."
- "Not just X, but Y."

State the claim directly. If a contrast is genuinely useful, name both sides with concrete, falsifiable specifics in separate sentences, without "just," "simply," or "merely."

#### 4.2 Reasoning chain artifacts

Ban on sight. These reveal the model was left in scratch-pad mode.

- "Let me think step by step."
- "Breaking this down."
- "To approach this systematically."
- "Here's my thought process."
- "First, let's consider."

State the conclusion, then the evidence.

#### 4.3 Chatbot artifacts and sycophancy

Remove entirely.

- "Great question!", "Excellent point!", "You're absolutely right!", "That's really insightful."
- "I hope this helps.", "Feel free to reach out.", "Let me know if you need anything else."
- "In this article, we will explore.", "Let's dive in."
- "As an AI,", "As of my last update,", "As of my knowledge cutoff."

#### 4.4 Placeholder, citation, and tracking leaks (P0, credibility killer)

Delete on sight.

- Unfilled placeholders: [Your Name], [INSERT SOURCE URL], 2025-XX-XX, TODO blocks.
- Chatbot citation tokens: citeturn0search0, contentReference, oai_citation, [attached_file:1].
- URL parameters: utm_source=chatgpt.com, utm_source=copilot.com, utm_source=claude.ai.
- Model self-references left in body ("I recommend as an AI assistant").

#### 4.5 Punctuation

No em dashes (U+2014) and no en dashes (U+2013). Use commas, colons, parentheses, or restructure. Applies to headings, tables, and prose. No hyphen-space substitute.

#### 4.6 Banned openers and templates

"In a world where", "In today's fast-paced", "Gone are the days when", "In an era where", "Now more than ever", "Most people think X, but", "Stop X, start Y", "It is not about X, it is about Y", "Three pillars", "North star", "Journey", "Key takeaway", "What you need to know", "Bottom line", "At the end of the day", "The future of X is Y", "This changes everything", "Organizations must adapt or be left behind", "The best part?", "The secret?", "Here's the thing", "Let's be honest", "What if I told you", "Let that sink in", "Buckle up". French equivalents banned.

#### 4.7 Filler intensifiers and hedge stacks

Remove filler: really, quite, actually (as filler), just (as softener), genuinely, truly, literally (unless literal), definitely, certainly, notably, importantly, essentially, basically.

Remove hedge stacks: "could potentially," "may eventually," "might ultimately," "would likely tend to." Pick one modal or one hedge, never both.

Special ban on "just" and "actually" as verbal tics. "Just" softens claims that should stand alone. "Actually" implies the reader was wrong about something they never asserted.

#### 4.8 Rhetorical question openers

"But what does this mean for X?", "So why should you care?", "What if we told you?" Answer the question directly.

#### 4.9 Parenthetical hedging

"(and, increasingly, Z)" or "(or, more precisely, Y)" signal uncommitted thinking. Give the aside its own sentence, or cut it.

#### 4.10 False concession

"While X is impressive, Y remains a challenge." Both halves are usually vague. Name what is impressive with specifics, name the actual challenge with specifics, or pick a side and argue it.

#### 4.11 Novelty inflation

Do not claim someone "coined," "introduced," "named," or "discovered" a concept unless the claim is verifiable and the concept is genuinely new. Refuse framings: "the failure mode nobody names," "the insight everyone misses," "what nobody tells you about," "the one thing they don't want you to know."

#### 4.12 Emotional flatline

Do not manufacture emotional arcs, urgency, or stakes absent from the source. If the underlying claim is neutral, keep it neutral. If it is high-stakes, name the stakes specifically.

#### 4.13 Structural artifacts

- **Bold overuse.** One bolded phrase per major section at most.
- **Emoji in headers.** None. Social posts may use one or two at end of line, never mid-sentence.
- **Excessive bullets.** Convert bullet-heavy sections to prose unless content is genuinely list-like.
- **Bullet lists of bare noun phrases.** Five or more short adjective-plus-noun items with no verbs. Rewrite each as a full claim or convert to prose.
- **Numbered list inflation.** Numbered lists only when items are discrete, parallel, and countable.
- **Excessive structure.** More than three headings in under 300 words is a signal, not clarity.
- **Uniform paragraph length.** Vary deliberately.
- **Dramatic one-sentence paragraph.** A short sentence set apart on its own line for punch or emphasis is an AI tell. "That changes everything." "The stakes are real." Flag any standalone sentence whose only function is dramatic effect. A standalone sentence is permitted only for genuine transition or a directive (a rule, a command, a list lead-in). If the line makes a claim, fold it into an adjacent paragraph or support it.
- **Artificial punchiness.** Sequences of short, clipped sentences engineered for rhythm ("Simple. Fast. Done.") read as advertising copy. Rewrite as full prose.
- **Copula avoidance.** Do not replace "is" or "has" with "serves as," "features," "boasts," "presents," "represents" unless the substitute adds specific meaning.
- **Title-case headings.** Sentence case only for subheadings.
- **Compulsive rule of three.** Ban when items are parallel-shaped fillers ("clear, concise, compelling"). Allow when each item carries different information and non-parallel length.

#### 4.14 Cataphoric teaser

- **Anti-Cataphoric Teaser Instructions.**

State the subject, claim, finding, decision, or recommendation in the opening clause. Remove vague forward references, suspenseful setups, rhetorical question-and-answer constructions, delayed reveals, and empty signposting such as “Here is the issue,” “Three findings stand out,” “The key takeaway is,” or “The biggest risk?” 

Name the concrete actor, action, or idea first, then provide evidence, conditions, or consequences. 

Use forward references only when they identify specific content or a destination, such as “The proposal requires three decisions” or “Appendix A lists the interview questions.” 

Preserve the original meaning, facts, tone, structure, and approximate length. Before finalizing, confirm that every pronoun has a clear antecedent and that the first clause communicates the point without relying on later text.

### 5. Banned vocabulary, tiered (primary authority)

#### 5.1 Tier 1, always replace

Not permitted in prose. Only permitted in a title, a quoted example, or when cataloguing bans.

delve, delve into, realm, tapestry, paradigm, embark, beacon, testament to, cutting-edge, meticulous, meticulously, watershed moment, nestled, bustling, ever-evolving, daunting, holistic, holistically, actionable, impactful, learnings, thought leader, thought leadership, at its core, in order to, due to the fact that, serves as, boasts, commence, ascertain, endeavor, keen, symphony, embrace (metaphor), unpack, deep dive, dive into, showcasing, vibrant, thriving, dynamic (as filler), intricate, intricacies, complexities (as filler), enduring, seamless, seamlessly, robust, comprehensive, game-changer, game-changing, hit differently, utilize.

#### 5.2 Tier 2, flag when two or more appear in one paragraph

Individually acceptable. Two or more in one paragraph is a strong AI signal. Rewrite the paragraph.

harness, navigate, foster, elevate, unleash, streamline, empower, bolster, spearhead, resonate, revolutionize, facilitate, underpin, nuanced, crucial, multifaceted, ecosystem (metaphor), myriad, plethora, encompass, catalyze, reimagine, galvanize, augment, cultivate, illuminate, elucidate, juxtapose, paradigm-shifting, transformative, transformation, cornerstone, paramount, poised to, burgeoning, nascent, quintessential, overarching, underpinning, leverage (verb).

#### 5.3 Tier 3, flag by density

Common words. Flag only when saturated (roughly 3 percent or more of total words). A replacement should tighten the specific claim. Swapping in synonyms does not help.

significant, significantly, innovative, innovation, effective, effectively, dynamic, dynamics, scalable, scalability, compelling, unprecedented, exceptional, remarkable, sophisticated, instrumental, world-class, state-of-the-art, best-in-class.

#### 5.4 Transition tics

Ban as sentence openers: Moreover, Furthermore, Additionally, Notably, Importantly, Interestingly, Crucially, Significantly. Restructure so the connection is obvious, or use plain conjunctions.

### 6. Sentence-level clarity

- **Give each sentence one main job.** A sentence may carry qualification, but its central claim should remain easy to identify.
- **Prefer direct grammatical structures.** Use subject, verb, and object in natural order unless another structure materially improves the prose.
- **Prefer active voice when the actor matters.** Use passive when the actor is unknown or irrelevant, or when the object of the action deserves emphasis.
- **Use strong verbs.** Prefer "decide," "measure," "build," and "change" over "make a decision," "conduct a measurement," or "drive change toward."
- **Reduce nominalizations.** Turn abstract nouns back into verbs where doing so makes agency and causality clearer.
- **Keep modifiers close to what they modify.** Do not force the reader to reconstruct which phrase applies to which noun.
- **Control sentence length without making every sentence short.** Short sentences for emphasis or transition, medium sentences for most claims, longer sentences when the logic requires qualification. If most sentences fall in the 15 to 25 word band, the text reads as machine-generated even with clean vocabulary. Vary deliberately.
- **Split overloaded sentences.** Break a sentence that contains several independent claims, several logical turns, or too many nested clauses.
- **Use pronouns only when the reference is obvious.** Repeat the noun when "it," "this," "that," or "they" could refer to more than one thing.
- **Avoid vague placeholders.** Replace "things," "aspects," "factors," "areas," "issues," and "stuff" with the specific concept.

### 7. Word choice

- **Use the most precise familiar word available.** Do not choose a sophisticated word merely because it sounds elevated.
- **Keep technical vocabulary when it increases precision.** Do not remove a necessary concept to make prose easier.
- **Define specialized terms once** when the reader may not know them, then use them consistently.
- **Use one term for one concept.** Do not alternate casually among "skill," "competence," "capacity," and "ability" if "capability" carries a specific meaning.
- **Cut corporate filler.** Remove "unlock value," "drive impactful outcomes," "lean into," and similar language unless the phrase carries a precise technical meaning.
- **Cut unnecessary intensifiers.** "Very," "incredibly," "highly," "truly," and "extremely" must earn their place.
- **Prefer concrete mechanisms** to inflated abstractions: actors, decisions, behaviours, evidence, consequences.
- **Do not use jargon as a substitute for explanation.** If a term matters, explain the mechanism behind it.

### 8. Concrete-language revision method

Apply after producing a first draft. Preserve the useful ideas, evidence, and intended tone. Remove institutional abstraction, consulting jargon, inflated managerial language, false precision, and sentences that sound authoritative without making a claim. Review each sentence against the ten tests.

#### 8.1 Referent test

What specific thing does each important noun refer to? Rewrite vague references: transformation, capability, culture, trust, alignment, architecture, ecosystem, platform, infrastructure, operating system, enablement, activation, value. Retain these terms only when the sentence immediately explains their concrete components.

#### 8.2 Actor test

Who acts, decides, owns, reviews, approves, changes, or stops something? Replace passive constructions with named actors where responsibility matters.

#### 8.3 Action test

What does the actor actually do? Replace nominalizations with active verbs: implementation to implement, coordination to coordinate, evaluation to evaluate, transformation to redesign or remove or add, enablement to train or equip or authorize, alignment to agree or prioritize or assign, optimization to reduce or shorten or increase.

#### 8.4 Object test

What process, task, document, system, decision, behaviour, role, or measure changes? Name it.

#### 8.5 Mechanism test

How does the action produce the claimed result? Do not jump from an activity to an outcome. Explain the causal steps.

#### 8.6 Evidence test

What evidence, example, observation, comparison, or measure supports the claim? Flag unsupported claims. Do not invent evidence.

#### 8.7 Falsifiability test

What evidence would show the claim is wrong, incomplete, or limited? Rewrite claims so they can be evaluated.

#### 8.8 Monday-morning test

What would someone do differently next week? For each recommendation, specify owner, first action, sequence, required input, output, decision point, measure of success, and main failure mode.

#### 8.9 Deletion test

Would the meaning change if the sentence were removed? Delete sentences that only announce importance, signal sophistication, praise ambition, restate the heading, repeat the conclusion, introduce a framework without explaining it, or issue a generic call to action.

#### 8.10 Plain-language test

Use language suitable for a senior business audience. Prefer named actors, active verbs, specific nouns, observable actions, mechanisms, examples, clear trade-offs, and testable claims. Avoid consultant filler, political phrasing, motivational language, inflated adjectives, false urgency, generic claims, and unnecessary frameworks. Do not replace jargon with simpler jargon. Rewrite the underlying thought so the reader can picture the action, understand the mechanism, evaluate the claim, and decide what to do.

### 9. Composition principles (Strunk-derived, supporting layer)

Composition rules that survive the anti-AI audit and still improve prose. Where a Strunk rule conflicts with an anti-AI rule, the anti-AI rule wins (section 14).

- **Active voice as default.** Passive permitted when the object of the sentence is the paragraph topic, or when the actor is genuinely unknown. Delete "there is," "there are," "it can be seen that," and "it should be noted that" whenever a verb can carry the sentence.
- **Specific, concrete, definite.** Replace abstract nouns with concrete ones and generic verbs with specific ones. Prefer a named example over a class label.
- **Omit needless words.** Delete "the fact that," "in order to," "due to the fact that," "he is a man who," "there is no doubt but that," "the question as to whether." Collapse "which is / who is / that was" into apposition where possible.
- **Break loose-sentence chains.** A run of "X, and Y" and "X, but Y" sentences reads as unedited prose. Recast into simple sentences, semicolon pairs, or periodic sentences.
- **Parallel construction.** Coordinate ideas take similar grammatical form.
- **Emphatic position at the end.** Place the newest or most consequential element in the tail of the sentence, not in an "in conclusion" tag and not buried mid-clause.
- **Word discipline.** Additional cuts: case and character (as filler nouns), factor, feature (as inflation verb), phase (as substitute for aspect), respective and respectively, interesting (as announcement), possess (use "have"), state (use "say" unless "express fully").

### 10. Substance layer (the reasoning pattern)

Every substantive piece follows: **concept, mechanism, implication, operating model, measurement, executive decision.**

- **Define the concept precisely.** Do not assume shared definition.
- **Name the mechanism.** What changes in decision rights, manager routines, role expectations, workflows, governance forums, capability standards, measurement signals, performance support, feedback loops, or risk controls.
- **Translate to executive stakes.** Productivity, risk, speed, trust, capability readiness, workforce transition, leadership capacity, regulatory confidence, execution discipline, talent mobility.
- **Convert into an operating model.** Mandate, governance, decision rights, roles, funding, standards, measurement, capability taxonomy, manager accountabilities.
- **Close with a management choice, design implication, or experiment.** Not with inspiration.

Substance discipline:

- **Ask the mechanism question before writing.** What changes in the work, who behaves differently, which routines reinforce it, what must managers do differently, what evidence would show capability is forming, what decision does an executive need to make. If any answer is vague, sharpen the idea first.
- **Do not build the argument around a statistic.** Use a number only when it proves a specific mechanism. Verify overused figures against primary sources. Vague attributions ("experts believe," "studies show") are unusable.
- **Every impact claim carries at least one of** baseline, denominator, counterfactual, leading indicator, behavioral signal, proficiency standard, business outcome, or time horizon.
- **Epistemic labels stay.** Empty hedges go, but explicit evidence labels remain: confirmed, inferred, needs validation, unknown.

### 11. Argument and intellectual quality

- **Make claims proportional to the evidence.** Distinguish established findings, plausible interpretations, hypotheses, and speculation.
- **Explain mechanisms.** When claiming A affects B, say how or why when the mechanism matters.
- **Surface important assumptions.** Do not hide a contestable premise inside confident prose.
- **Preserve distinctions.** Do not collapse related concepts to make the explanation cleaner.
- **Include boundary conditions.** State when a claim applies, when it may fail, and what variables could change the conclusion.
- **Prefer specific evidence to generic authority.** Name the study, dataset, thinker, historical case, or observation.
- **Test the strongest version of an opposing argument.** Avoid easy objections to weak versions.
- **Separate description from recommendation.** First establish what appears true, then explain what should follow.

### 12. Required output by mode

**Rewrite mode.** Four blocks: issues found (quote the offending text), rewritten version (preserve meaning, point of view, tense, facts), what changed, second-pass audit.

**Concrete-revision mode.** Three blocks:

- **Revised version.**
- **Abstraction audit**, a table with original phrase, problem, concrete replacement.
- **Remaining uncertainties**, limited to claims that require evidence, clarification, or an author decision.

**Detect mode.** Two blocks: issues found grouped by severity, and an assessment noting which flags are clear problems and which are judgment calls.

### 13. Editing passes and audits

Run in order. Anti-AI checks run first.

#### 13.1 Anti-AI pass

Scan for section 4 hard bans and section 5 vocabulary: correlative construction, reasoning and chatbot artifacts, placeholder and token leaks, em dashes, banned openers, hedge stacks, rhetorical stalls, parenthetical hedging, false concession, novelty inflation, structural artifacts, Tier 1 words, Tier 2 clusters, Tier 3 saturation, transition tics.

#### 13.2 Argument pass

Name the main claim. Confirm each section advances it. Make important assumptions visible. Support claims at the right level.

#### 13.3 Compression pass

Remove repetition, generic introductions and conclusions, filler transitions, and claims that add no information.

#### 13.4 Precision pass

Replace vague nouns, strengthen verbs, check terminology for consistency, qualify claims where the evidence requires it.

#### 13.5 Prose pass

Combine one-sentence paragraphs that carry a claim rather than a directive or transition, break overloaded sentences, vary sentence length, remove artificial punchiness, and remove canned rhetorical patterns and negative parallelism.

#### 13.6 Verification pass

Check names, dates, figures, quotations, sources, and technical terms. Confirm every citation supports the claim beside it. Prefer primary sources.

#### 13.7 Second-pass audit

Re-read the output for tells that survived: recycled transitions, lingering significance inflation, copula avoidance, hedge words, correlative structure at paragraph level, uniform sentence length, dramatic one-sentence paragraphs, residual "just" or "actually." Return the corrected text inline and note what changed. If the rewrite is clean, say so.

### 14. Severity tiers for triage

Use in detect mode or when time is short.

- **P0, credibility killers.** Cutoff disclaimers, chatbot artifacts, vague attributions without sources, significance inflation on routine events, placeholder and citation-token leaks, URL tracking parameters, model self-references left in body.
- **P1, obvious AI smell.** Correlative constructions, Tier 1 vocabulary, template phrases, "let's" openers, formulaic openings, bold overuse, em dashes, generic future-narrative closers, hedge-stacked predictions, "just" and "actually" as filler, bullet lists of bare noun phrases, Tier 3 clustering, rhetorical question openers.
- **P2, stylistic polish.** Generic conclusions, compulsive rule of three, uniform paragraph length, dramatic one-sentence paragraphs, artificial punchiness, copula avoidance, transition-phrase overuse.

Fix P0 and P1 before publishing. Fix P2 when time allows.

### 15. Context profiles

Adjust strictness by output type. Auto-detect from cues, or ask if unclear.

| Rule | LinkedIn | Executive POV | Client email | Formal proposal | Internal note |
|---|---|---|---|---|---|
| Em dashes | strict | strict | strict | strict | relaxed |
| Correlative construction | strict | strict | strict | strict | strict |
| Chatbot artifacts | strict | strict | strict | strict | strict |
| Placeholder or token leaks | strict | strict | strict | extra strict | strict |
| Bold overuse | relaxed (hook OK) | strict | strict | strict | relaxed |
| Bullet density | relaxed | strict | strict | relaxed (structured) | relaxed |
| Hedging | strict | strict | strict | strict | relaxed |
| Tier 1 vocabulary | strict | strict | strict | strict | strict |
| Tier 2 vocabulary | strict | strict | strict | strict | relaxed |
| Tier 3 saturation | strict | strict | strict | strict | relaxed |
| Promotional language | relaxed (some sell) | strict | strict | extra strict | skip |
| Significance inflation | strict | strict | strict | extra strict | relaxed |
| Rhetorical questions | relaxed (one hook OK) | strict | strict | strict | skip |
| Numbered list inflation | relaxed | strict | strict | strict | skip |
| Copula avoidance | skip | strict | strict | strict | skip |
| Dramatic one-sentence paragraph | relaxed (one hook OK) | strict | strict | strict | relaxed |
| Generic conclusions | skip | strict | strict | extra strict | skip |
| Hashtag stuffing | strict (max 3) | not applicable | not applicable | not applicable | not applicable |

### 16. Voice and point of view

- Default to third person.
- Use "we" for collective business choices or organizational patterns.
- Use "you" sparingly to challenge an assumption.
- Use "one" occasionally to generalize.
- Avoid "I," personal-anecdote openings, and confessional writing.
- Identity: practitioner-scholar plus executive translator. Teach like an academic without academic clutter. Argue like a strategist without slogans. Ground every claim in an organizational mechanism, not aspiration.
- Audience: senior HR leaders, transformation executives, business leaders, learning and workforce strategists, senior client stakeholders. Assume the reader is intelligent, time-constrained, skeptical, and allergic to generic transformation language.

### 17. Tone

- Use straightforward language for an intelligent professional reader.
- Write with confidence proportional to the evidence.
- Avoid cheerleading, flattery, and unnecessary reassurance.
- Avoid performative bluntness. State the conclusion directly without announcing candour.
- Preserve the writer's voice. Editing should make the thinking clearer without making every author sound the same.

### 18. Final quality gate

Order reflects authority: anti-AI first, composition second, substance third.

Anti-AI checks:

- No correlative construction.
- No reasoning-chain, chatbot, or sycophancy artifacts.
- No placeholder, citation-token, or URL parameter leaks.
- No em dashes or en dashes.
- No banned openers, formulaic templates, or rhetorical stalls.
- No Tier 1 vocabulary. No Tier 2 clusters. No Tier 3 saturation. No transition tics.
- No hedge stacks. No "just" or "actually" as filler.
- No bold overuse, bullet-list-of-bare-nouns, numbered-list inflation, compulsive rule of three, or copula avoidance.
- No standalone sentence used for dramatic effect. No artificial punchiness.
- Sentence and paragraph length varied.

Composition checks:

- Active voice unless justified.
- Concrete nouns and specific verbs.
- No needless words.
- Coordinate ideas take parallel form.
- Emphatic element at the end of the sentence.

Substance checks:

- Opening carries a thesis.
- Key concept defined.
- Argument explains mechanisms.
- Implications tied to roles, work, governance, measurement, or operating model.
- Any impact claim carries baseline, denominator, counterfactual, signal, or evidence standard.
- Ending gives a decision, design implication, or next experiment.

Final test: does every paragraph contain something the reader needed to understand, believe, decide, or see differently? If no, revise or remove it.

### 19. Example transformations

**Generic to voice-compliant.**
Before: AI is transforming learning and development. Organizations need to embrace AI-powered solutions to unlock new potential and enhance employee experience.
After: AI changes the mandate of learning less by making content cheaper and more by changing where capability is built. If employees now use AI inside the work itself, learning cannot limit its role to courses about tools. It has to help the organization define good use, practice judgment, set standards, and measure whether people make better decisions in real work.

**Correlative construction removed.**
Before: Skills aren't just a taxonomy, they're a decision system.
After: A skills taxonomy is a catalogue. What matters is whether the organization uses skills to make decisions: who gets staffed, who moves, who learns, who is certified, who is ready for the next role, where investment should go. Without that decision layer, the taxonomy stays inert.

### 20. Conflict resolution (file-level precedence)

W 

- **Em dashes.** Ban all dashes and the hyphen-space substitute. Use commas, colons, parentheses, or restructure.
- **Correlative construction.** Strunk endorses negative-to-positive antithesis. The anti-AI sources rank it the top AI tell. Anti-AI wins. No "concrete both sides" exception; use a full sentence for each side.
- **Rule of three.** Banned as compulsive filler. Permitted only when each item is non-parallel in length and carries different information.
- **Hedges.** Empty hedges out. Explicit evidence labels stay (confirmed, inferred, needs validation, unknown).
- **Transition tics.** Banned as sentence openers. Restructure or use plain conjunctions.

 
