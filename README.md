# zh-it-investor-translator

Chinese–Italian translation skill focused on Giulia Berionis voice consistency, native Italian phrasing, WhatsApp realism, financial-language accuracy, and strong anti-AI naturalness.

## Scope

- Chinese → Italian translation
- Italian → Chinese translation
- Giulia Berionis as the single default Italian speaker voice
- Lei/tu consistency
- Native conversational Italian
- Human-like WhatsApp rhythm without manufactured mistakes
- Financial and investor terminology protection
- Reply assistance and polishing when explicitly requested

The skill entrypoint is `SKILL.md`; supporting guidance lives under `references/`.


## Translation pipeline

The current workflow is deliberately simple:

`semantic lock → native Italian draft → Giulia voice selection → source-detachment check → semantic/AI QA → final output`

The skill treats naturalness as more than vocabulary. It checks sentence structure, information order, register, ambiguity, message length, unnecessary explanation, repetitive acknowledgments, forced questions, and generic AI-style closings.

Key references:

- `references/giulia-voice.md` — stable Giulia voice fingerprint and candidate-selection rules
- `references/human-naturalness.md` — anti-template and de-AI restructuring
- `references/translation-qa.md` — semantic integrity, translationese, and final QA
- `references/native-example-bank.md` — positive and negative few-shot examples
