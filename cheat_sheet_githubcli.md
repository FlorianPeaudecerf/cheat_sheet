# GITHUB CLI CHEAT SHEET  
### GITHUB PULL REQUEST
| command |description  |
|---------|-------------|
|gh pr status      |Show status of relevant pull requests             |
|gh pr list         |List open pull requests in repo             |
|gh pr list -s all         |List all pull requests in repo|
|gh pr view ['number'  'url'  'branch']         |View a pull request             |
| gh pr checkout        |Checkout a pull request in Git             |
| gh pr create -t 'title' -b 'body'        |Create a new pull request|
### GITHUB ISSUES
| command | description |
|---------|-------------|
| gh issue status        |Show status of relevant issues             |
| gh issue list        |List open issues in repo             |
| gh issue list -s all        |List all issues in repo             |
| gh view ['number' 'url']        |View an issue             |
|gh issue create -t 'title' -b 'body'         |Create a new issue|
### GITHUB REPOSITORIES
| command | description |
|---------|-------------|
|gh repo clone 'repo'         |Clone a repository locally             |
| gh repo create 'name repo'        |Create a new repository             |
| gh repo fork 'repo'        |Create a fork or a repository             |
| gh repo view 'repo'        |View a repository             |
### GITHUB COMMAND
| command | description |
|---------|-------------|
| gh --version        |Display GitHub CLI version             |
| gh help        |Show help info             |
| gh <pr  issue  repo> --help        |Show help info for a specific command group             |
| gh <pr  issue  repo> 'command' --help        |Show help info for a specific command             |
