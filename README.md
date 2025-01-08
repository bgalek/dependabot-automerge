# Dependabot Auto Merge
This GitHub Action automatically approves and merges pull requests created by Dependabot.

> Dependabot will wait until all your status checks pass before merging. This is a function of Dependabot itself, and not this Action.

## Usage

Add permissions

```yaml
permissions:
  contents: write
  pull-requests: write
  id-token: write
```

Use the action

```yaml
    steps:
      - uses: bgalek/dependabot-automerge@v1
```

Happy hacking!
