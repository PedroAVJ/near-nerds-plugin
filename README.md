# Nier Nerds plugin

Ask your agent what someone likes to build or talk about, using only their [published profile](https://nier-nerds.pedroavj.chatgpt.site). You can also draft your own profile from **your own** Codex and Claude conversations. You review the exact public text before anyone publishes it. Each device contributes only the history available on that device; raw chats stay local.

## Install in Codex

```sh
codex plugin marketplace add PedroAVJ/nier-nerds-plugin
codex plugin add nier-nerds@nier-nerds
```

Start a new Codex task after installation. Ask, for example, “Nier Nerds, what is Pedro into?” or “Nier Nerds, draft my profile from my Codex and Claude threads.”

## Install in Claude Code

```sh
claude plugin marketplace add PedroAVJ/nier-nerds-plugin
claude plugin install nier-nerds@nier-nerds
```

Start a new Claude Code session after installation. Its skill can read the same published profile data and prepare a draft from the conversation history available in Claude.

Public profile data: [index](https://nier-nerds.pedroavj.chatgpt.site/profiles/index.json) · [agent guide](https://nier-nerds.pedroavj.chatgpt.site/llms.txt)

## Publishing

The Nier Nerds Site owner merges an approved JSON profile into the Site repository and deploys it. The plugin never uploads raw conversations. The second profile stays empty until its owner chooses what to share.
