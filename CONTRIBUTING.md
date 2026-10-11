# Contributing

- run `npm test` before a pull request with Node 22 or newer
- one source file per language, no code comments, names carry the meaning
- deletions beat additions, and a new file needs a reason the README can state
- keep the dead-ends table current when you learn why something fails
- claims about macOS or Claude behavior come with the Claude Code and Desktop versions you verified

Use a synthetic HOME for tests. App-control commands and cloud operations are mocked. Set `npm_config_offline=true npm_config_update_notifier=false` to prevent npm's update check.

When process inspection is denied, focused fixtures can preload an empty `/bin/ps` result and a not-running `/usr/bin/pgrep` result. Tests that enumerate real processes need `ps` access.

Run `swiftc -typecheck -parse-as-library menubar.swift`. The `@main` app needs library parsing.
