# Git HOw to:
1. `git add .`
1. `git commit -m "fix stuff"`
1. `git push`

# Git how to (SSH edition):
1. Install `openssh'
1. `ssh-keygen -t ed25519 -C "<email>"`
1. `eval "$(ssh-agent -s)"`
1. `ssh-add <path to key>`
1. `ssh -T git@github.com`
1. Back to the [first step](#git-how-to)
