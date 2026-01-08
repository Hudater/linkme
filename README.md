# linkme

## My personal fork with added features

### Branching

- `main` deploys with my own customizations
- `feat` branches are used to develop features
- `upstream-parity-branch` is used to keep track of [upstream](https://github.com/ironicbadger/linkme)

A customizable link page generator built in Go.

![A screenshot of the application.](assets/screenshot.png)

## Usage

```bash
# Build the static site
go run ./cmd/linkme build

# Serve locally
go run ./cmd/linkme serve
```

## Docker

```bash
docker run -d -p 8080:80 ghcr.io/hudater/linkme:latest
```

## Configuration

Edit `config/config.yaml` to customize your links and appearance.
