# Ember for Mac

Ember is a private AI companion for your wellbeing that lives in your menu bar. It talks things through with you,
remembers what matters, notices how your day is going, checks in at sensible moments, and helps you turn deadlines
into small daily steps. Everything runs on your Mac: the model, your conversations and everything Ember learns about
your day stay on it.

**Ember is an AI, not a therapist or a crisis service.** If you're in crisis, contact your local emergency number or
find a free helpline at [findahelpline.com](https://findahelpline.com/).

## Requirements

- A Mac with Apple silicon, running macOS 26 or later
- 16 GB of memory or more for Ember's own model, or [LM Studio](https://lmstudio.ai) with a model of your choice

Website: [la-harris.github.io/ember-mac](https://la-harris.github.io/ember-mac/)

## Install

1. Download the latest `Ember-<version>.dmg` from [Releases](https://github.com/la-harris/ember-mac/releases/latest),
   open it and drag Ember to Applications.
2. Open Ember. The first time, macOS says it can't check the app for malicious software: click **Done**.
3. Open **System Settings > Privacy & Security**, scroll to Security, and click **Open Anyway** next to Ember.
4. From then on Ember opens like any other app. It keeps itself up to date (it asks first); Settings > About has the
   switch.

On first run Ember asks where its model should run. Ember's own model is coming soon; until then, install
[LM Studio](https://lmstudio.ai), download a model (Gemma 4 works well) and start its server. You can change this any
time in Settings.

## Privacy

Ember has no servers and no accounts. It contacts the internet only to download its model once and, if you allow it,
to check this page for updates.

Made by LAH.
