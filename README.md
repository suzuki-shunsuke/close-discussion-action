# close-discussion-action

GitHub Action to close and lock GitHub Discussions.

[action.yaml](action.yaml)

## Requirements

- GitHub CLI
- GitHub Access Token
  - repositories: a repository where the action is executed
  - permissions: `discussions: write`

## Usage

```yaml
- uses: suzuki-shunsuke/close-discussion-action@main
  with:
    number: 10 # Required. Discussion Number
```

## Inputs / Outputs

Please see [action.yaml](action.yaml)

## LICENSE

[MIT](LICENSE)
