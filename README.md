# tor-proxychains4-mac

```
# installation:
> brew install tor
> brew install proxychains-ng

# running tor and proxychains:
> brew services restart tor
> proxychains4 -f proxychains.conf curl ipinfo.io

# socksify terminal command:
> export http_proxy=socks5://127.0.0.1:9050
> export https_proxy=socks5://127.0.0.1:9050
```
