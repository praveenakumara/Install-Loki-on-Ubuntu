# Install Loki on Ubuntu 22.04

## Install Loki

Get the latest version tag of Loki from GitHub.

```
LOKI_VERSION=$(curl -s "https://api.github.com/repos/grafana/loki/releases/latest" | grep -Po '"tag_name": "v\K[0-9.]+')
```