# venue-utils

Dalamud plugins for FFXIV venue hosts, published by The Succubus Den.

> **No support will be provided. This software is to be used as is, without warranty of any kind.**

## Install

In game open /xlsettings, Experimental, Custom Plugin Repositories, paste `https://raw.githubusercontent.com/The-Succubus-Den/venue-utils/main/pluginmaster.json`, tick the box and Save.

- [StripDeathroll14](https://github.com/The-Succubus-Den/StripDeathroll14) — Strip Deathroll host helper: turn order, roll calls, wrong-roll alerts, lives and round history.

## How it updates

`pluginmaster.json` is rebuilt every hour by `.github/workflows/update-pluginmaster.yml` from the latest `latest.zip` release of each repo in `repos.json` (all under `github.com/The-Succubus-Den`). Run that workflow by hand to pick up a release straight away.
