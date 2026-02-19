# TranslateBot

**Automate Django translations with AI.** Repeatable, consistent, and pennies per language.

TranslateBot is a dedicated tool that sits between "do it by hand" and "pay for a platform" - built for ongoing projects where translations need to stay in sync as your code changes.

---

## The Problem

Translating a Django app sounds simple until it isn’t:

- **Manual workflow doesn’t scale.** Copy strings to Google Translate, paste back, fix placeholders, repeat for every language. It works for 20 strings. It falls apart at 200.
- **AI assistants work once, but not repeatedly.** You can ask ChatGPT or Claude Code to translate a `.po` file, and it’ll do a decent job. Once. Next sprint, when 15 new strings appear, you’re prompting from scratch, re-translating the whole file, and hoping it stays consistent.
- **SaaS translation platforms are expensive overkill.** Paid localization services charge per-word subscriptions and come with portals, review workflows, and team features you don’t need for a solo project or small team.

---

## Why TranslateBot?

- **Incremental.** Only translates new and changed strings. Add 10 strings in a sprint, pay for 10 strings, not the whole file.
- **Consistent.** A `TRANSLATING.md` file in your repo acts as a version-controlled glossary: terminology, tone, brand rules. Every translation run uses it.
- **Cost-efficient.** Batches strings into optimized API requests. A typical app costs under $0.01 per language with GPT-4o-mini.
- **Scales to many languages.** One command translates all your configured languages. Adding a new locale is a one-liner.
- **Automatable.** A CLI command you can script or hook into your workflow. No browser, no portal.
- **Placeholder-safe.** Preserves `%(name)s`, `{0}`, `%s`, and HTML tags with 100% test coverage on format string handling.

---

## Try it with Django

```bash
uv add --dev translatebot-django
python manage.py translate --target-lang nl
```

No new file formats. No vendor lock-in.

---

## Supported frameworks

| Framework | Package | Status |
|---------|--------|--------|
| Django | [translatebot-django](https://github.com/gettranslatebot/translatebot-django) | Available |
| More | — | Planned |

---

## Resources

- 📘 Documentation: [translatebot.dev](https://translatebot.dev)
- 📦 PyPI: [translatebot-django](https://pypi.org/project/translatebot-django/)
- 🐛 Issues & feedback welcome

---

## License

Released under the **Mozilla Public License 2.0** — open source, business-friendly.
