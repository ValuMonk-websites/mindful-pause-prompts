# Mindful Pause — pause questions

This repository holds one file, `prompts.json`: the questions the Mindful Pause app shows on its pause screen, in English and Hinglish.

Phones with Mindful Pause download this file about once a day. The download is one-way: the app sends nothing about its user or their phone. A file that fails the app's checks is ignored, and the phone keeps its last good copy.

The questions are written and checked in the app's own (private) repository, in `prompts/prompt-bank.md`, and copied here with `tools/make_prompts_json.py`. Please don't edit `prompts.json` here by hand.
