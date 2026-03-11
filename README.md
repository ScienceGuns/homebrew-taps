Homebrew Taps
=============
This repo contains a few custom Homebrew taps to make installing our internal tooling easier. Many of these tools are also publicly accessible.

Usage
-----
To use this repo you can tap it with
```bash
brew tap ScienceGuns/homebrew-taps
```  

List the tools we have availalbe via
```bash
brew tap-info ScienceGuns/taps --json | jq -r '.[]|(.formula_names[],.cask_tokens[])'
```
