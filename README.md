# Claude Code plugins by pravnyadv

Add this marketplace once:

```
/plugin marketplace add pravnyadv/claude-plugins
```

Then install what you need:

| Plugin | What it does | Install |
|---|---|---|
| [safekeys](https://github.com/pravnyadv/claude-safekeys) | Give Claude Code your API keys without putting them in the chat. `$:NAME=value` goes to your OS keychain, and Claude only sees `$NAME`. | `/plugin install safekeys@pravnyadv` |
| [monday-tasks](https://github.com/pravnyadv/monday-claude) | Work with monday.com from Claude Code: read and update tasks, post updates, and track which session worked on which task and MR. | `/plugin install monday-tasks@pravnyadv` |

Run `/reload-plugins` or start a new session after installing.

Each plugin lives in its own repo, and that's where the code, docs and issues are. This repo only lists them, so updates arrive as soon as a plugin's repo changes.

## License

[MIT](LICENSE). Each plugin carries its own license in its repo.
