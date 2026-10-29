# Natural technical content

Technical writing should make the reader competent, not impress them with the product or the author.

## Organize around the reader's task

Put the main outcome first. Add only the sections the task needs, commonly:

- purpose or expected result;
- prerequisites and permissions;
- steps in execution order;
- observable result or verification;
- troubleshooting and rollback.

Do not force this outline onto a one-paragraph answer. Do not repeat the introduction in a conclusion.

## Procedures

- Use an imperative verb for an action: «Откройте», «Введите», «Запустите».
- Put conditions before the instruction: «Если сервер возвращает 401, обновите токен».
- Keep one action per numbered step unless the actions are inseparable.
- Use numbered lists for sequences and bullets for unordered sets.
- Name UI controls exactly as they appear. Format commands, code, paths, parameters, and literal values consistently.
- Describe the expected result where it helps the reader confirm progress.
- Put warnings before the step that creates the risk. State the consequence and a safer option or recovery path.

## Explain systems precisely

Name the actor. Prefer «Сервер отклоняет запрос» to «Запрос отклоняется», and «После сохранения сервис отправляет уведомление» to «Будет осуществлена отправка уведомления».

Use present tense for current product behavior. Distinguish clearly:

- required: «нужно», «must», or a direct imperative;
- optional: «можно», “can”;
- possible outcome: «может», “might”;
- recommendation: say who recommends what and why.

Avoid ambiguous «следует» and “should” when the reader needs to know whether something is required, expected, or merely recommended.

Keep technical terms when they are more accurate than a plain-language substitute. Do not preserve internal jargon just because it appears in the draft. Prefer a familiar equivalent when it preserves meaning; otherwise define an unfamiliar term once and use it consistently. Check product documentation or a glossary before translating an ambiguous term. Do not rename the same object for stylistic variety. For Russian choices and examples, use [russian-editorial.md](russian-editorial.md).

## Sound knowledgeable, not mechanical

- Prefer specifics over generic benefits: latency, limits, file types, permissions, failure modes, and actual behavior.
- Avoid “easy”, “simple”, «легко», «просто», and «очевидно» in instructions. They add no help and can blame readers who get stuck.
- Avoid pre-announcements such as «В этом разделе мы рассмотрим…» when the heading already says it.
- Use active voice by default, but keep passive voice when the actor is unknown or the result matters more.
- Mix sentence lengths only as the explanation requires. Do not turn every sentence into the same 8–15-word unit.
- Use examples that are realistic, internally consistent, and safe to copy. Do not invent production data or credentials.

## Release notes and change descriptions

Tell the reader what changed, who is affected, and whether they need to act. Avoid promotional framing and empty claims of improvement.

- Weak: «Мы рады представить важное обновление, значительно улучшающее пользовательский опыт».
- Better: «Черновики теперь сохраняются при потере соединения. Дополнительных действий не требуется».

## Final accuracy pass

Verify commands, names, defaults, version constraints, links, and described UI states. If information is uncertain, state the uncertainty or request the missing source instead of smoothing it over with confident prose.

Sources: [Google developer documentation style guide: Highlights](https://developers.google.com/style/highlights), [Google: Voice and tone](https://developers.google.com/style/tone), [Google: Second person and first person](https://developers.google.com/style/person), [Google: Prescriptive documentation](https://developers.google.com/style/prescriptive-documentation), [Microsoft: Top 10 tips for style and voice](https://learn.microsoft.com/en-us/style-guide/top-10-tips-style-voice), [GOV.UK: Use clear language](https://guidance.publishing.service.gov.uk/writing-to-gov-uk-standards/writing-guidelines/clear-language/).
