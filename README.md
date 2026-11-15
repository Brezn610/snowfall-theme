# Snowfall theme

A dark winter-night theme for Claude Code on desktop and mobile. The backdrop is a moonlit scene with a cabin and pine trees. Snow falls behind the conversation, and the snowfall grows as the session's context window fills: more flakes, deeper drifts, and a small ring badge in the top-left corner showing the context percentage. The mod hooks `turn.step`, reads the session usage after each model response, and redraws the backdrop. No setup is needed; install it and start a session.

The scene is drawn in `hooks/scene.js`: a distant snowy range, pines at three depths (each tier lit on the side facing the moon, shaded under the tier above, with snow on its boughs), and a log cabin with lit windows, a lantern, icicles and a smoking chimney. As the context fills, the snow on the boughs and the roof thickens and the front drift rises around the cabin.

## Install

In Claude Code:

```
/plugin install snowfall-theme --marketplace Brezn610/snowfall-theme
```

or from a shell:

```
claude plugin marketplace add Brezn610/snowfall-theme
claude plugin install snowfall-theme@snowfall
```

The repository is public, so no GitHub sign-in is needed to install it; the machine only needs `git`. (If the repository is ever made private, each machine needs GitHub access to it, for example `gh auth login` or a `GITHUB_TOKEN` in the environment.) Start a new session afterwards; the backdrop appears once the first message is sent.

## Credits

Parts of the forest are adapted from the snow-pines scene in Anthropic's [theme-examples](https://github.com/anthropics/claude-plugins-official/tree/main/plugins/theme-examples) plugin (Apache License 2.0). See `THIRD_PARTY_NOTICES.md` and `licenses/Apache-2.0.txt`.
