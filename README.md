# linkme

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
docker run -d -p 8080:80 ghcr.io/ironicbadger/linkme:latest
```

## Configuration

Edit `config/config.yaml` to customize your links and appearance.

### Analytics

Google analytics and Goatcounter currently allowed

If `Goatcounter.selfhosted=True`: id is used as domain therefore user need to provide FQDN
in ID
else: `id` is prepended to `.goatcounter.com`
