# zh-it-investor-translator

A focused Chinese–Italian translation Skill built around one simple goal:

**Express what each side really means in language a native speaker immediately understands, while keeping one stable Giulia Berionis voice and a natural human feel.**

## What it does

- Chinese -> native Italian
- Italian -> natural Chinese
- Giulia Berionis as the single default outgoing Italian voice
- Lei/tu consistency
- natural WhatsApp-style phrasing
- financial terminology and action protection
- polishing and de-AI rewriting when requested
- explanation or reply assistance only when explicitly requested

## Design principle

The Skill intentionally stays simple:

`understand meaning -> protect meaning -> express natively -> make it sound human`

It does not use customer profiling, personality inference, or a large multi-stage translation system.

## Files

- `SKILL.md` — core translation behavior
- `references/giulia-voice.md` — stable Giulia style
- `references/financial-language.md` — financial terminology and semantic distinctions
- `references/native-example-bank.md` — native vs translated-sounding examples
- `agents/openai.yaml` — Skill metadata
- `assets/icon.svg` — icon

The main principle is simple: if a new rule does not improve **meaning accuracy, native clarity, Giulia consistency, or human naturalness**, it does not belong here.
