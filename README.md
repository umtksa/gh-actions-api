# gh-actions-api

```sh
  curl --request POST \
  --url 'https://api.github.com/repos/JoshDanielWalker/gh-actions-api/dispatches' \
  --header 'authorization: Bearer <Your personal access token here>' \
  --data '{"event_type": "update", "client_payload": {"message": "hello","debug": "true"}}'
```
