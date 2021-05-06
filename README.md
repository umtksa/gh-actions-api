# gh-actions-api

Using the Github Api to tigger a Github Action to update a JSON file, which can be used by a website as an API using Github Pages for free. 

```sh
  curl --request POST \
  --url 'https://api.github.com/repos/JoshDanielWalker/gh-actions-api/dispatches' \
  --header 'authorization: Bearer <Your personal access token here>' \
  --data '{"event_type": "update", "client_payload": {"message": "hello","debug": "true"}}'
```
