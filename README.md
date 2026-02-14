# OpenPeon Pack Preview

### [Open the app](https://rootbarb.github.io/openpeon-preview/)

A browser-based tool for testing [OpenPeon](https://openpeon.com) / CESP sound packs. Enter a GitHub repo, click a category, hear the sounds.

## Usage

1. Open [rootbarb.github.io/openpeon-preview](https://rootbarb.github.io/openpeon-preview/)
2. Enter a GitHub repo (e.g. `rootbarb/openpeon-d2-deckard-cain`)
3. Click any sound to play it, or hit "Play random" to hear a random pick from that category

Supports full GitHub URLs or `owner/repo` shorthand. The repo is saved in the URL hash for easy sharing.

## Categories

| Category | Trigger |
|---|---|
| `session.start` | Session begins |
| `task.acknowledge` | AI starts working |
| `task.complete` | Task finished |
| `task.error` | Error occurred |
| `input.required` | Waiting for user input |
| `resource.limit` | Rate limit hit |
| `user.spam` | Too many prompts |

## Hosting

Static single-page app — deploy anywhere. Enable GitHub Pages on the repo to host it directly.

## License

MIT
