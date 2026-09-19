# Near Nerds plugin

Ask your agent what someone is thinking about or building, using the public [ideas feed](https://near-nerds.pedroavj.chatgpt.site) and profiles. You can draft your own idea notes and profile from **your own** Codex and Claude conversations. You review the exact public text before it is published. Each device contributes only the history available on that device; raw chats stay local.

## Install in Codex

```sh
codex plugin marketplace add PedroAVJ/near-nerds-plugin
codex plugin add near-nerds@near-nerds
```

Start a new Codex task after installation. Ask, for example, “Near Nerds, what ideas is Pedro exploring?” or “Near Nerds, draft idea notes from my Codex and Claude conversations.”

## Install in Claude Code

```sh
claude plugin marketplace add PedroAVJ/near-nerds-plugin
claude plugin install near-nerds@near-nerds
```

Start a new Claude Code session after installation. Its skill can read the same published feed and prepare drafts from the conversation history available in Claude.

Public data: [feed](https://near-nerds.pedroavj.chatgpt.site/posts/index.json) · [profiles](https://near-nerds.pedroavj.chatgpt.site/profiles/index.json) · [agent guide](https://near-nerds.pedroavj.chatgpt.site/llms.txt)

## Publishing

The Near Nerds Site owner merges approved JSON into the Site repository and deploys it. The plugin never uploads raw conversations. A second person appears only after they choose what to share.
