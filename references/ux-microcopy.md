# UX microcopy patterns

Write for the moment in the flow. The interface, state, and available actions carry part of the meaning; do not repeat what the layout already makes obvious.

## Buttons and links

- Name the action and, when needed, its object: «Сохранить», «Открыть черновик», «Удалить отчёт».
- Match the button to the promise in the heading and body. Do not tell the reader to open a draft and label the button «Продолжить».
- Use generic «ОК» only for acknowledgement when no more specific action exists.
- Distinguish actions with different outcomes. Do not use two buttons that both read «Продолжить».
- Make link text understandable out of context. Avoid «здесь», «подробнее», and “click here” when a destination can be named.

## Errors

Give the reader the smallest complete recovery path:

1. say what failed or what input needs attention;
2. say why only when the cause is known and useful;
3. provide the next action;
4. mention saved or lost data when that affects the decision.

Do not blame the reader, expose an internal error code as the only explanation, or fabricate a cause. Avoid «что-то пошло не так», «некорректное значение», «вы забыли», «недопустимо», “invalid”, and “an error occurred” when a specific message is possible.

- Weak: «Пожалуйста, заполните поле корректно».
- Better: «Введите ИНН из 10 или 12 цифр».
- Weak: «Произошла ошибка загрузки».
- Better when the cause is known: «Файл больше 20 МБ. Выберите файл меньшего размера».
- Better when the cause is unknown: «Не удалось загрузить файл. Попробуйте ещё раз».

Keep the user's entered values after validation errors. Use the same terms in the field label, inline error, and error summary.

Reserve an apology for a serious service failure where the product caused meaningful disruption. “Sorry” or «извините» does not replace recovery guidance.

## Confirmations and destructive actions

Name the object and consequence. A generic «Вы уверены?» asks the reader to reconfirm an intention they already have.

- Weak: «Удалить доверенность? Это действие нельзя отменить».
- Better: «После удаления Анна не сможет отправлять отчёты за ООО „Маяк“».
- Destructive button: «Удалить доверенность».

Prefer undo or recovery over repeated confirmation when the action is frequent and technically reversible.

## Empty states

Explain the absence only if it is not obvious, then give the next relevant action. Do not use a cheerful dead end.

- Weak: «Здесь пока ничего нет».
- Better: «Нет сохранённых отчётов» with «Создать отчёт» when that action exists.

Distinguish a first-use empty state from no search results, filtered results, missing permissions, and a loading failure; they need different copy and actions.

## Success, loading, and progress

State the completed action: «Отчёт отправлен», not «Отчёт успешно отправлен». Add a next step only if the reader needs one.

For waiting states, name the ongoing action: «Загружаем отчёт…». If the wait is meaningful, show progress or a realistic expectation. Do not substitute «Пожалуйста, подождите» for status.

## Headings, labels, hints, and tooltips

- Front-load the distinctive information. Readers often scan only the heading and first words.
- Make a page heading describe the page's task or content.
- Use labels that remain visible when a field contains a value; placeholders are examples or hints, not replacements for labels.
- Add help text only when it prevents a likely error or answers a real question.
- Identify the tooltip's anchor and the question it raises. Help beside a term can define its meaning or scope; help for a control can explain a consequence or constraint. Do not add an instruction or a condition merely because a control is nearby.
- A tooltip should add the smallest useful explanation. Read it with its label, remove redundant introductions, and preserve words needed to distinguish objects or message types. An explanation can be a noun phrase; it does not always need a verb or «Это…».
- Essential requirements, errors, and consequences needed to make a decision should be visible in the flow. A tooltip should not compensate for a routinely confusing interface.
- Do not refer only to color, position, size, or shape: «зелёная кнопка справа» is not accessible.

## Voice and Russian usage

Be calm, helpful, and adult. Use «вы» in lowercase unless the product's house style requires otherwise. Avoid ceremonial politeness, forced jokes, exclamation marks, and corporate enthusiasm during errors or stressful tasks.

Use familiar user vocabulary. Explain necessary domain terms on first use. Keep numbers, units, dates, and object names specific when they help the reader decide.

Sources: [Контур.Гайды: «Текст в интерфейсе»](https://guides.kontur.ru/principles/text/styleguide/), [Контур.Гайды: UX-ревью интерфейса](https://guides.kontur.ru/principles/user-research/interfacecheck/), [GOV.UK: Writing for user interfaces](https://www.gov.uk/service-manual/design/writing-for-user-interfaces), [GOV.UK Design System: Error message](https://design-system.service.gov.uk/components/error-message/), [Apple HIG: Buttons](https://developer.apple.com/design/human-interface-guidelines/buttons).
