---
name: human-ux-writing
description: Write, review, or rewrite Russian and English UX microcopy and technical content in clear, concise, well-structured language. Reduce jargon and bureaucratic phrasing while preserving meaning. Use for buttons, labels, errors, empty states, onboarding, help text, product copy, release notes, instructions, and developer documentation.
---

# Human UX writing

Produce text that helps a real reader complete a real task. Human-sounding prose is a result of judgment, specificity, and context—not slang, typos, invented anecdotes, or attempts to evade AI detectors.

## Start from the situation

Before drafting, identify what can be inferred from the request or product:

- who is reading and what they are trying to do;
- where the text appears and what the reader sees before and after it;
- what happened, what is known, and what action is available;
- the product's terminology, voice, length limits, and accessibility needs.

For screenshots and mockups, identify the exact element the text belongs to: follow callout arrows and inspect nearby labels, controls, and states. Determine whether the reader needs a definition, a consequence, a requirement, or an instruction; write to that need. A help icon next to a term may need to define it, while help for a control may need to explain its effect. Let the actual context decide.

Preserve the user's established voice and house style. If there is no house style, use a calm, direct, knowledgeable voice. Ask a question only when missing context would materially change the action, promise, risk, or factual meaning. Never invent a cause, capability, deadline, user quote, or product behavior to make copy sound concrete.

## Draft from facts and actions

Lead with the answer to the reader's immediate question: a meaning, outcome, state, or next useful action. Prefer concrete nouns and active verbs. Address the reader directly when it helps, and use the imperative for steps. Keep one term for one concept.

Use familiar words in the reader's language. Existing copy is not proof that its jargon is necessary. Replace internal slang and unnecessary English when a familiar equivalent is accurate. Preserve established product terms, identifiers, and distinctions; explain an unfamiliar term when needed. If its meaning is unverified, do not invent a translation.

Give each sentence a job: provide a fact, explain a consequence, guide an action, or supply necessary context. Remove sentences that only announce, summarize, praise, transition, or restate nearby text.

Organize by the reader's questions before polishing individual words. Keep each paragraph about one point; use lists for real sets or sequences. Shorten until the text is easy to use, preserving actors, objects, conditions, and relationships. Repeating a noun is useful when it prevents ambiguity. Do not optimize for a word quota or readability score.

Use simple forms of “быть”, “есть”, “is”, “are”, and “has” when they are the clearest choice. Do not inflate them into “служит”, “выступает”, “представляет собой”, “serves as”, “features”, or “offers” merely to sound polished.

## Remove machine-like patterns

Read [references/ai-patterns.md](references/ai-patterns.md) when humanizing existing prose or reviewing AI-assisted content. Treat the patterns as diagnostic clues, not banned words. Fix the underlying problem: missing evidence, vague meaning, generic praise, mechanical structure, or unearned certainty.

Do not deliberately add mistakes, choppiness, fake personal detail, or random sentence-length variation. Natural rhythm should follow the content: short for actions and states, longer only when a relationship or condition needs explanation.

## Choose the relevant writing mode

- For Russian writing or Russian localization, read [references/russian-editorial.md](references/russian-editorial.md): vocabulary choices, sentence structure, concise phrasing, and a practical editing pass. Combine it with the relevant mode below.
- For interface copy, errors, buttons, empty states, confirmations, loading, and notifications, read [references/ux-microcopy.md](references/ux-microcopy.md).
- For help articles, procedures, API documentation, release notes, and technical explanations, read [references/technical-content.md](references/technical-content.md).
- For a mixed product flow, use both. Keep UI labels consistent with the documentation that names them.

## Verify the result

Before delivering:

1. Check every factual claim, number, link, product name, and stated cause against the available evidence.
2. Confirm that the text answers the question raised by its element or situation. Include a next action only when the reader needs one.
3. Remove generic openings, ceremonial conclusions, repeated summaries, and decorative claims of importance.
4. Read the text aloud. Rewrite anything that sounds bureaucratic, promotional, patronizing, or unnaturally symmetrical.
5. Check scanning and language: headings and first words should carry meaning; lists should form a real set; jargon should have a reason to remain; shortening must not change scope, conditions, or obligations.
6. If the text lives in an implemented interface, inspect it in context when possible: truncation, neighboring labels, states, responsive layout, and the complete task flow.

Do not call a text “AI-generated” based on style alone. When reviewing, name the observable issue and its effect on the reader.

## Deliver

For a rewrite, put the finished copy first. Add rationale or alternatives only when the user asks or when a consequential tradeoff needs explanation. For a review, pair each meaningful issue with a concrete revision. Preserve domain terms that the audience needs; explain them on first use instead of replacing them with less accurate everyday words.

When alternatives are requested, vary a meaningful choice such as emphasis, length, or assumed reader knowledge. Avoid offering several near-identical word orders as different solutions. Recommend one and give a brief, context-specific reason.
