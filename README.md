# issuenote

> A GitHub App to add note to a web page, saving notes to github issues

## Setup

```sh
# Install dependencies
npm install

# Compile
npm build

# Run the bot
npm start
```

## Docker

```sh
# 1. Build container
docker build -t issuenote .

# 2. Start container
docker run -e APP_ID=<app-id> -e PRIVATE_KEY=<pem-value> issuenote
```

## Contributing

If you have suggestions for how issuenote could be improved, or want to report a bug, open an issue! We'd love all and any contributions.

For more, check out the [Contributing Guide](CONTRIBUTING.md).

## License

[ISC](LICENSE) © 2021 Mike Y <bayhiker@users.noreply.github.com>
