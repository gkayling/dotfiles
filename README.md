# grega does dotfiles

## dotfiles

Your dotfiles are how you personalize your system. These are mine.

If you're interested in the philosophy behind why projects like these are
awesome, you might want to [read this post on the
subject](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/).

## install

Run this:

```sh
git clone https://github.com/gkayling/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
```

This will symlink the appropriate files in `.dotfiles` to your home directory.
Everything is configured and tweaked within `~/.dotfiles`.
