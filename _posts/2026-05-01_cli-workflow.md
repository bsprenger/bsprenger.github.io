```bash
alias fdiff='git add -N . && \
  git diff --name-only | \
  fzf --preview "git diff --color=always {}" \
      --preview-window=right:60% --header \
      "ENTER: View Full Diff | CTRL-E: Edit in Neovim" \
      --bind "enter:execute(git diff --no-prefix -U10000 --color=always {} | tail -n +5 | less -R)" \
      --bind "ctrl-e:execute(nvim {})"'
```
