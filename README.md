# jms1-cheatsheets

This repo contains a small collection of "cheatsheets" I use, for the [cheat](https://github.com/cheat/cheat/) command, both for work and in my personal life.

You're welcome to look at them, copy them, use them however you like. However, everybody is different, so if you're going use [cheat](https://github.com/cheat/cheat), you'll probably want to start your own list of personal cheatsheets.

## My Configuration

If it helps, this is the `$HOME/.config/cheat/conf.yml` file I use on my workstations. (The path for `bbedit` depends on the machine, for Intel-based macOS machines use `/usr/local/bin/bbedit`.)

```yaml
# https://github.com/cheat/cheat
---
# The editor to use with 'cheat -e <sheet>'. Defaults to $EDITOR or $VISUAL.
editor: /opt/homebrew/bin/bbedit

# Should 'cheat' always colorize output?
colorize: true

# Which 'chroma' colorscheme should be applied to the output?
# Options are available here:
#   https://github.com/alecthomas/chroma/tree/master/styles
style: monokai

# Which 'chroma' "formatter" should be applied?
# One of: "terminal", "terminal256", "terminal16m"
formatter: terminal256

# Through which pager should output be piped?
# 'less -FRX' is recommended on Unix systems
# macOS/Linux are recommended on Windows
pager: less -FRX

# Cheatpaths are paths at which cheatsheets are available on your local
# filesystem.
cheatpaths:
  - name     : community
    path     : /Users/jms1/git/cheat/cheatsheets
    tags     : [ community ]
    readonly : true

  - name     : jms1
    path     : /Users/jms1/git/jms1-cheatsheets/cheatsheets
    tags     : [ jms1 ]
    readonly : false
```
