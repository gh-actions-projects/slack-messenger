# Slack Messenger

A simple composite action build on top of other slack-messager to smplify the steps.

### Usage

```yml
- name: slack
  uses: gh-actions-projects/slack-messenger@v1.0.0
  with:
    webhook_url: ${{ secrets.SLACK_WEBHOOK_URL }}
    payload: happy birthday dani daniels
```
