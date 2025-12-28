# TranslateBot

AI-powered localization for your applications. Automate translations using LLMs like GPT-4, Claude, and Gemini.

## What is TranslateBot?

TranslateBot is an open-source CLI tool that automates translations using AI language models. It plugs into your existing i18n workflow, eliminating the manual work of keeping locale files in sync.

Get started at [translatebot.dev](https://translatebot.dev).

## Features

- **Multi-Provider Support** — Works with OpenAI, Anthropic Claude, Google Gemini, Azure OpenAI, and more via LiteLLM
- **Placeholder Preservation** — Safely handles `{variables}`, HTML tags, and format strings
- **Dry-Run Mode** — Preview changes before writing to files
- **Selective Overwriting** — Only translate new or changed strings
- **Low Cost** — ~$0.01 per language for typical small apps using GPT-4o-mini

## Supported Frameworks

| Framework | Package | Status |
|-----------|---------|--------|
| Django | [translatebot-django](https://github.com/gettranslatebot/translatebot-django) | Available |

## Resources

- [Documentation](https://translatebot.dev)
- [PyPI Package](https://pypi.org/project/translatebot-django/)

## License

TranslateBot is released under the [Mozilla Public License 2.0](https://www.mozilla.org/en-US/MPL/2.0/).
