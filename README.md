# Laptop bootstrap script

Read, then run the script:

    bash <(curl -s https://raw.githubusercontent.com/fredoliveira/laptop/master/mac) 2>&1 | tee ~/laptop.log

# What it sets up

* [Bundler] for managing Ruby libraries
* [Exuberant Ctags] for indexing files for vim tab completion
* [gh] for interacting with the GitHub API
* [Homebrew] for managing operating system libraries
* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [Rbenv] for managing versions of Ruby
* [RCM] for managing company and personal dotfiles
* [Ruby Build] for installing Rubies
* [Ruby] stable for writing general-purpose code
* [Tmux] for saving project state and switching between projects
* [Zsh] as your shell

[Bundler]: http://bundler.io/
[Exuberant Ctags]: http://ctags.sourceforge.net/
[gh]: https://github.com/jingweno/gh
[Homebrew]: http://brew.sh/
[Node.js]: http://nodejs.org/
[NPM]: https://www.npmjs.org/
[Rbenv]: https://github.com/sstephenson/rbenv
[RCM]: https://github.com/thoughtbot/rcm
[Ruby Build]: https://github.com/sstephenson/ruby-build
[Ruby]: https://www.ruby-lang.org/en/
[Tmux]: http://tmux.sourceforge.net/
[Zsh]: http://www.zsh.org/

# License

Laptop is © 2011-2015 thoughtbot, inc.
It is free software, and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE
