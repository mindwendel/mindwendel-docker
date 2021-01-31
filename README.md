# mindwendel docker

Create a challenge. Ready? Brainstorm. mindwendel helps you to easily brainstorm and upvote ideas and thoughts within your team. Built from scratch with [Phoenix](https://www.phoenixframework.org). See main repo for more information.

## Getting Started

Build the image
```sh
docker build .
```

Run the image
```sh
docker run -it -p 127.0.0.1:80:4000 -e DATABASE_HOST="host.docker.internal" -e DATABASE_USER="..." -e DATABASE_USER_PASSWORD="..." -e DATABASE_NAME="..." -e SECRET_KEY_BASE="..." -e URL_HOST="localhost" IMAGE_ID_HERE
```

SECRET_KEY_BASE has to be a random 64 char long string. You can generate one using e.g. elixir/phoenix (if installed):

```sh
mix phx.gen.secret
```

## Contributing

1. Fork it (<https://github.com/mindwendel/mindwendel/fork>)
2. Create your feature branch (`git checkout -b fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin fooBar`)
5. Create a new Pull Request

## Acknowledgements

- https://github.com/JannikStreek
- https://github.com/gerardo-navarro
- https://github.com/nwittstruck
