# lazynitro-cli

[![stability-wip](https://img.shields.io/badge/stability-wip-lightgrey.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#work-in-progress)

Python CLI to help download nitro, download models and run them, in a single command (plus args) 😛

TODO:
- [ ] Support installing via pipx using just the GitHub link
- [ ] Download nitro automatically during first run, using XDG path or the defined path by user
- [ ] Download tinyllama as default model (into XDG path) and run it if model name is not provided
- [ ] Interactive or listing mode to help the user to browse models and choose what to download
- [ ] Support single-option config file: name/id of the default model to run
- [x] Be lazy and ready to be able to setup an alias command with full of args for putting into your dotfiles. Then on your headless machine you can run a single alias command to do things you want!
