# gh-actions-api

Using the Github Api to tigger a Github Action to update a JSON file, which can be used by a website as an API using Github Pages for free. 


## 1 - Github Api to tigger a Github Action
```sh
  curl --request POST \
  --url 'https://api.github.com/repos/JoshDanielWalker/gh-actions-api/dispatches' \
  --header 'authorization: Bearer <Your personal access token here>' \
  --data '{"event_type": "update", "client_payload": {"message": "hello","debug": "true"}}'
```
## 2 - Github Action updates JSON file

## 3 - Github Pages exposes JSON file as API
