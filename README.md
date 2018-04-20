# Site Saúde é meu lugar

http://www.saudeemeulugar.com/

## Usefull commands:

### Enter in docker compose containers:

```sh
docker-compose exec api bash
```

### Add submodule:

```sh
git submodule add git@github.com:saudeemeulugar/site.git server/site
```

```sh
git submodule add git@github.com:saudeemeulugar/admin.git client/admin
```

## On clone:

```sh
git submodule update --init --recursive
```

