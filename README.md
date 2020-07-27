# Git user config Github Action

An action that globally configures git for specified GitHub user.

## Usage

```yaml
- name: Configure git
  uses: dawidd6/action-git-user-config@v1
  with:
    # Defaults to $GITHUB_ACTOR if not specified
    username: BrewTestBot
```
