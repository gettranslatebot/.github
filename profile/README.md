# TranslateBot

**Automate i18n translations without breaking your locale files.**

TranslateBot is open-source tooling for developers who want to keep gettext and other i18n files up to date using LLMs — safely, cheaply, and inside existing workflows.

---

## Why TranslateBot?

If you’ve ever:
- Manually translated `.po` files
- Broken `{placeholders}` or HTML tags
- Paid too much for small string updates

TranslateBot is built for that exact problem.

---

## What it does

- **Preserves formatting** — placeholders, HTML, and format strings stay intact
- **Fits existing workflows** — works with your current i18n setup
- **Only translates what changed** — no unnecessary overwrites
- **Dry runs supported** — see changes before writing files
- **Provider-agnostic** — OpenAI, Claude, Gemini, Azure via LiteLLM
- **Low cost by default** — ~$0.01 per language for small apps (GPT-4o-mini)

---

## Try it with Django

```bash
pip install translatebot-django
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

- 📘 Documentation: https://translatebot.dev
- 📦 PyPI: https://pypi.org/project/translatebot-django/
- 🐛 Issues & feedback welcome

---

## License

Released under the **Mozilla Public License 2.0** — open source, business-friendly.
