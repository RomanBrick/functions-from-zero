# functions-from-zero
live training

[![Codespaces Prebuilds](https://github.com/RomanBrick/functions-from-zero/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/RomanBrick/functions-from-zero/actions/workflows/codespaces/create_codespaces_prebuilds)

### To call Microservice 

something like this
```bash
curl -X 'POST' \
  'https://noahgift-functions-from-zero-r7g59wcxx6x-8080.githubpreview.dev/wiki' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "name": "Microsoft"
}'
```

### Build container

`docker build .`
`docker image ls`

### Run container

something like this

`docker run -p 127.0.0.1:8080:8080 a81ce4f35866`

### Invoke POST request

run `invoke.sh`

## References

* [Watch Walkthrough on YouTube](https://youtu.be/KOAdCqpQSI4)

