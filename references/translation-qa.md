# Translation QA: Meaning, Native Flow, and De-AI Review

Use this reference for important translations, polish requests, medium or long messages, financial/client content, or whenever the output must feel strongly human and native.

The goal is not to make the text more elaborate. The goal is to catch meaning drift, translationese, and AI-style overproduction before output.

## Review order

Always review in this order:

1. semantic integrity;
2. speech act and register;
3. native Italian flow;
4. translationese;
5. AI-pattern residue;
6. final compression.

Never optimize style before meaning is locked.

## Pass 1: Build a semantic contract

Before rewriting, silently identify the source's non-negotiable elements:

- people, companies, products, places;
- numbers, dates, prices, percentages, tickers;
- negation;
- time reference;
- action state;
- modality and certainty;
- risk language;
- Lei/tu clues;
- emotional temperature;
- speech act;
- ambiguity that must remain unresolved.

For investment language, explicitly classify the action:

- observing;
- following;
- evaluating;
- considering;
- buying;
- opening a position;
- adding;
- holding;
- reducing;
- selling;
- taking profit;
- stopping out.

Do not allow stylistic rewriting to move the text from one class to another.

## Pass 2: Native rewrite

Translate or rewrite for target-language meaning rather than source-language order.

A good draft should:

- use idiomatic Italian collocations;
- use Italian information order;
- split or merge clauses only when meaning is unchanged;
- preserve the source's degree of politeness;
- preserve ambiguity;
- avoid literal Chinese discourse fillers;
- preserve the original message length roughly when possible.

Quality question:

> If the source were hidden, would this look like original Italian?

## Pass 3: Translationese detector

Check for visible source-language fingerprints.

Common Chinese-to-Italian translationese includes:

- topic-first structures preserved when Italian would start with the action;
- repeated subjects;
- repeated nouns instead of pronouns or omission;
- too many `attualmente`, `inoltre`, `pertanto`, `per quanto riguarda`;
- support-verb phrases such as `effettuare un investimento` when `investire` is natural;
- literal translations of `进行`, `根据`, `关注`, `推送`, `目前`;
- long comma chains mirroring Chinese punctuation;
- unnatural repetition of courtesy language.

When detected, restructure rather than merely replace synonyms.

## Pass 4: AI-pattern detector

Check whether the text has patterns that are grammatical but too generated.

Flag:

- automatic acknowledgment at the start;
- `Capisco perfettamente` or similar generic empathy;
- response structure of `acknowledge -> explain -> reassure -> ask`;
- sentence lengths that are too even;
- perfectly balanced three-part wording;
- unnecessary transitions;
- repeated summaries;
- generic positive closings;
- forced questions;
- service-language endings;
- over-explanation of obvious context;
- expansion of short source text into polished prose.

The preferred fix is subtraction.

## Pass 5: Backward semantic audit

Do not literally back-translate word for word.

Instead, compare the Italian draft against the semantic contract:

- Did every factual element survive?
- Was anything added?
- Was anything omitted?
- Did certainty change?
- Did a suggestion become stronger?
- Did a question become more leading?
- Did a refusal become softer or harder?
- Did an investment action change?
- Did Lei/tu change?
- Did ambiguity disappear without evidence?

If any answer indicates drift, fix meaning before style.

## Error priority

### Critical

Must fix:

- invented content;
- omitted material meaning;
- wrong number, date, price, ticker, name, or negation;
- changed investment action;
- changed certainty or risk level;
- mixed Lei/tu;
- changed refusal/consent/commitment meaning.

### Major

Should fix:

- non-native collocation;
- strong translationese;
- excessive formality;
- obvious source-language word order;
- AI-style expansion;
- repeated acknowledgment or explanation;
- unnatural closing or forced question.

### Minor

Fix only if useful:

- punctuation preference;
- small rhythm issue;
- two equally natural word choices;
- harmless stylistic variation.

Do not rewrite a good translation repeatedly chasing minor issues.

## One-rewrite rule

For ordinary chat and short messages:

- draft once;
- run the QA checks;
- if a real issue exists, rewrite once;
- stop.

Repeated polishing can make natural chat less natural by making it too perfect.

For longer or high-stakes text, one additional review pass is acceptable.

## Minimal output rule

QA is internal unless the user asks for analysis.

For pure translation:

- output only the final translation;
- do not expose the semantic contract;
- do not show rejected candidates;
- do not mention the review;
- do not add confidence labels.

## Quick QA examples

Source:
`有时间您可以看看，不一定要买。`

Bad drift:
`Quando ha tempo, le consiglio di acquistarlo se le sembra interessante.`

Problem:
The source says there is no obligation to buy; the translation turned evaluation into a recommendation to purchase.

Better:
`Quando ha tempo può dargli un'occhiata, senza alcun obbligo di acquistare.`

Source:
`最近没有怎么关注股票。`

Overtranslated:
`Recentemente non ho prestato particolare attenzione al mercato azionario, poiché sono stato impegnato con altre questioni.`

Problem:
The reason was invented.

Better:
`Ultimamente non ho seguito molto il mercato azionario.`

Source:
`好的，那先这样。`

AI-ish:
`Va bene, capisco perfettamente. Per il momento possiamo procedere in questo modo e, se dovessero esserci novità, potremo valutarle insieme.`

Problem:
Acknowledgment, explanation, and future collaboration were added.

Better:
`Va bene, per ora facciamo così.`
