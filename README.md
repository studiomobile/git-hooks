This repo contains Git hooks for adding a branch name to the start of the commit message.

For example, `<feature/add-something> Add very useful stuff`.

Doesn't add a branch name if a commit message starts with `<`.

To install, simply copy files from `hooks` folder to `.git/hooks` folder of your Git project. After that, execute `chmod +x .git/hooks/*`.