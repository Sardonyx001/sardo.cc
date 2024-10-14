# forgejo

Selfhosted [forgejo](https://codeberg.org/forgejo/forgejo) instance.
It's gitea but without any corporate nonsense and drama.

## how?

Deployed straight from its [docker image](https://codeberg.org/forgejo/-/packages/container/forgejo/versions) `codeberg.org/forgejo/forgejo:8` .
Initial setup takes care of all the configurations.

## things to look out for

Since Cloudflare doesn't proxy ssh traffic you might have to disable
proxying for the (sub)domain the instance is on.

## port mappings

```yaml
ports:
  - 3000:3000
  - 2222:22
```

ps: make sure to open port 2222 on your firewall

```sh
sudo ufw allow 2222/tcp
```
