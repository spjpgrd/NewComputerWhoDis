NewComputerWhoDis
======

NewComputerWhoDis is a shell script that gets your machine ready for design and development.

This script can be ran once or as many times as you'd like. It installs everything that macOS needs to get to work.

## Requirements

* macOS (>10)

## Install

**Step One:** Download the script
```sh
curl --remote-name https://raw.githubusercontent.com/spjpgrd/NewComputerWhoDis/master/macos
```

**Step Two:** Run it
```sh
sh macos 2>&1 | tee ~/NewComputerWhoDis.log
```

## Debugging

The log of your script, successful or not, will be saved to `~/NewComputerWhoDis.log`.

Read through it to see if you can debug the issue yourself.
If not, report where the script failed into a [new GitHub Issue](https://github.com/spjpgrd/NewComputerWhoDis/issues/new).

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
7. camunda-modeler
8. cfxr
9. color-oracle
10. dash
11. dropbox
12. dropzone
13. firefox
14. flip4mac
15. handbrake
16. imagealpha
17. imageoptim
18. iterm2
19. keyboard-cleaner
20. Keyboard-maestro
21. lastfm
22. lastpass
23. licecap
24. google-chrome
25. noun-project
26. opera
27. screenflow
28. sequel-pro
29. sketch
30. sketch-toolbox
31. soundflower
32. soundflowerbed
33. sublime-text
34. tower
35. vagrant
36. virtualbox
37. vlc
38. visual-studio-code
39. zoomus

## License

NewComputerWhoDis is © 2017 by Sean Doran and is protected under the [MIT License].

[MIT License]: LICENSE

## Credits and inspiration

Forked from Lauren Dorman's [komputer-maschine](https://github.com/laurendorman/komputer-maschine) which was inspired by thoughtbot's [laptop](https://github.com/thoughtbot/laptop/) and Andrew Taylor's article on [Pantheon](https://pantheon.io/blog/dev-setup-using-homebrew-os-x).
