# close-discussion-action

GitHub Action to close and lock GitHub Discussions.

<img width="254" alt="image" src="https://github.com/user-attachments/assets/d76e3b8a-61a4-4fba-80c8-e9a47a908a94">

You can also post a comment.

<img width="1285" alt="image" src="https://github.com/user-attachments/assets/3690aacd-90ba-4429-acfe-c2add2e3d639">

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
    number: 10 # id or number is required.
```

### :bulb: Close new discussions automatically

[Workflow](.github/workflows/close-discussion.yaml)

This workflow is useful if you want to stop creating new discussions while keeping existing discussions.

## Inputs / Outputs

Please see [action.yaml](action.yaml)

## LICENSE

[MIT](LICENSE)
