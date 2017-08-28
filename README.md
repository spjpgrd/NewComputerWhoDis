komputer maschine
======

komputer maschine is a shell script that gets your machine ready for design and development.

This script can be ran once or as many times as you'd like. It installs everything that macOS needs to get to work.

## Requirements

* A komputer maschine
* macOS (>10)

## Install

**Step One:** Download the script
```sh
curl --remote-name https://raw.githubusercontent.com/spjpgrd/komputer-maschine/master/macos
```

**Step Two:** Run it
```sh
sh macos 2>&1 | tee ~/komputer-maschine.log
```

## Debugging

The log of your script, successful or not, will be saved to `~/komputer-maschine.log`.

Read through it to see if you can debug the issue yourself.
If not, report where the script failed into a [new GitHub Issue](https://github.com/laurendorman/komputer-maschine/issues/new).

## What You Get

**macOS tools:**

* [XCode Command Line Tools](https://developer.apple.com/xcode/downloads/) for developer essentials.
* [Homebrew](http://brew.sh/) for managing operating system libraries.

**Unix tools:**

* [git](https://git-scm.com/) for version control.
* [tmux](http://tmux.github.io/) for saving project state and switching between projects.
* [zsh](http://www.zsh.org/) as your shell.

**Image tools:**

* [ImageMagick](http://www.imagemagick.org/) for converting, cropping, resizing and renaming images in the command line interface.

**Programming languages and configuration:**

* [Bundler](http://bundler.io/) for managing Ruby libraries.
* [Node.js](http://nodejs.org/) and [npm](https://www.npmjs.org/) for running applications and installing JavaScript packages.
* [Rbenv](https://github.com/sstephenson/rbenv) for managing versions of Ruby.
* [Ruby Build](https://github.com/sstephenson/ruby-build) for installing Rubies.
* [Ruby](https://www.ruby-lang.org/en/) stable for writing general-purpose code.

**Applications:**

1. audio-hijack
2. bartender
3. bettertouchtool
4. box-sync
5. brave
6. caffeine
7. cfxr
8. color-oracle
9. dash
10. dropbox
11. dropzone
12. firefox
13. flip4mac
14. handbrake
15. imagealpha
16. imageoptim
17. iterm2
18. keyboard-cleaner
19. Keyboard-maestro
20. lastfm
21. lastpass
22. licecap
23. google-chrome
24. noun-project
25. opera
26. screenflow
27. sequel-pro
28. sketch
29. sketch-toolbox
30. soundflower
31. soundflowerbed
32. sublime-text
33. tower
34. vagrant
35. virtualbox
36. vlc
37. visual-studio-code

## License

komputer maschine is © 2016 by Lauren Dorman and is protected under the [MIT License].

[MIT License]: LICENSE

## Credits and inspiration

Inspired by thoughtbot's [laptop](https://github.com/thoughtbot/laptop/) and Andrew Taylor's article on [Pantheon](https://pantheon.io/blog/dev-setup-using-homebrew-os-x).
