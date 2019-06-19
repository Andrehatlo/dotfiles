# My dotfile configuration:

### Based on Thoughtbots dotfiles:

1. Install thoughtbot's dotfiles: https://github.com/thoughtbot/dotfiles

2. Create ~/dotfile-local directory for custom configuration

3. Clone repository in your `$HOME` director

# What's in it?

I-Term configuration:

<img src="https://i.ibb.co/rGr3dmq/Screenshot-2019-06-19-at-10-10-30.png" alt="Screenshot-2019-06-19-at-10-10-30" border="0"><br />

vim configuration:

- Ctrl-P for fuzzy file/buffer/tag finding.
- Rails.vim for enhanced navigation of Rails file structure via gf and :A (alternate), :Rextract partials, :Rinvert migrations, etc.
- Run many kinds of tests from vim
- Set <leader> to a single space.
- Switch between the last two files with space-space.
- Syntax highlighting for Markdown, HTML, JavaScript, Ruby, Go, Elixir, more.
- Use Ag instead of Grep when available.
- Map <leader>ct to re-index ctags.
- Use vim-mkdir for automatically creating non-existing directories before writing the buffer.
- Use vim-plug to manage plugins.

tmux configuration:

- Improve color resolution.
- Remove administrative debris (session name, hostname, time) in status bar.
- Set prefix to Ctrl+s
- Soften status bar color from harsh green to light gray.

git configuration:

- Adds a create-branch alias to create feature branches.
- Adds a delete-branch alias to delete feature branches.
- Adds a merge-branch alias to merge feature branches into master.
- Adds an up alias to fetch and rebase origin/master into the feature branch. Use git up -i for interactive rebases.
- Adds post-{checkout,commit,merge} hooks to re-index your ctags.
- Adds pre-commit and prepare-commit-msg stubs that delegate to your local config.
- Adds trust-bin alias to append a project's bin/ directory to $PATH.

Ruby configuration:

- Add trusted binstubs to the PATH.
- Load the ASDF version manager.

Shell aliases and scripts:

- b for bundle.
- g with no arguments is git status and with arguments acts like git.
- migrate for rake db:migrate && rake db:rollback && rake db:migrate.
- mcd to make a directory and change into it.
- replace foo bar **/*.rb to find and replace within a given list of files.
- tat to attach to tmux session named the same as the current directory.
- v for $VISUAL.
