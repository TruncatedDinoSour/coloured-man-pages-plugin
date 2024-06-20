# This repository has been migrated to the self-hosted ari-web Forgejo instance: <https://git.ari.lt/ari/coloured-man-pages-plugin>
# Baz plugin: coloured-man-pages-plugin

> Baz plugin for Baz plugin for making your man pages colourful

# Installation

- Using [baz plugin manager](https://ari-web.xyz/gh/baz):

```bash
$ baz install git 'https://ari-web.xyz/gh/coloured-man-pages-plugin'
```

# Dependencies

- Man-db (man)
- Less pager

# Configuration

It's done though these environment variables:

- `CMAN_MB` has same effect as `LESS_TERMCAP_mb`, default: `\E[01;31m`
- `CMAN_MD` has same effect as `LESS_TERMCAP_md`, default: `\E[01;36m`
- `CMAN_SO` has same effect as `LESS_TERMCAP_so`, default: `\x1b[38;2;128;128;128m`
- `CMAN_US` has same effect as `LESS_TERMCAP_us`, default: `\E[04;36;146m`

# Looks

![man ls](/ss.jpg)
