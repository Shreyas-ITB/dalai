# Dalaiv2

**Please remember that this is a cloned version of [dalai library](https://github.com/cocktailpeanut/dalai). This version is updated based on the user's Pull Requests on the official library.**

## Current Version Changelog:

### Added some more AI models (Deprecated) DOES NOT WORK

1). Alpaca lora 7B, 13B and 30B models
2). gpt4 x alpaca 13B models
3). alpaca-7B-ne

### Codenames

**Normal versions**
`7B 13B 30B`
**LoRa versions**
`7B-lora 13B-lora 30B-lora`
**Native Enhanced versions**
`7B-ne`
**gpt 4 x alpaca 13B version**
`gpt4-x-alpaca-13B`

Use these code names to install different models ^

Example:

- ``npx dalaiv2 alpaca install 7B-lora``
- ``npx dalaiv2 alpaca install 7B-ne`` (7B Native Enhanced)
- ``npx dalaiv2 alpaca install gpt4-x-alpaca-13B``

**Also make sure to use ``dalaiv2`` after ``npx``. If you use ``dalai`` it uses the same official version.**

### Added some more prompts

Added chatbot-assistant

Added chatbot-bardClone

Added chatbot-fastQuestion

Added coding-jsComment2Code

Added coding-jsExplain

Added coding-jsQuestion

Added coding-pythonComment2Code

Added coding-question-alpaca

Added default (alpaca)

Added none

Added rephrase-bulletToText-alpaca

Added rephrase-fixGrammar

Added summarize-textToBullet

Added summarize-tldr

Added tweet-reply alpaca

Added tweet-sentiment

### Improved UX/UI

- Added new check mark in the UI to hide the prompt so that it will look more cleaner and easy to type!
- Fixed some bugs in the UX/UI and improved the UI CSS.
