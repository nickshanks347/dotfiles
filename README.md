# dotfiles

To update zsh in the repo:

1. `omz update`
2. `rm -rf .local/share/chezmoi/dot_oh-my-zsh/`
3. `chezmoi add .oh-my-zsh`
4. `cd .local/share/chezmoi`
5. `git add *`
6. `git commit -m "Update zsh"`
7. `git push`
8. Profit
