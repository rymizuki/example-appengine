# Example for AppEgine

## local

```console
> docker-compose up
```

## deploy

```console
> gcloud init
```

deploying for root service.
```console
> npm run build
> gcloud app deploy root
```

deploying for apis service.
```console
> gcloud app deploy apis
```