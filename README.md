# Pi-hole DNS

DNS filtering at home.  Configured with the following customizations [post-automated install](https://github.com/pi-hole/pi-hole/#one-step-automated-install).

## Lists

Custom block lists added to the Pi-hole under Adlists within Group Management.

* [Everything List from The Blocklist Project](https://github.com/blocklistproject/Lists#lists)
* Generated IPv4 and IPv6 Lists from [The YouTube ads blocklist project](https://github.com/Ewpratten/youtube_ad_blocklist)

## Upstream DNS Servers

### Custom 1 (IPv4)

[Cloudflare](https://1.1.1.3) malware and adult content blocking.

`1.1.1.3`

### Custom 2 (IPv4)

[Cloudflare](https://1.1.1.2) malware content blocking.


`1.1.1.2`

### Custom 3 (IPv6)

[Cloudflare](https://1.1.1.3) malware and adult content blocking.

`2606:4700:4700::1113`

### Custom 4 (IPv6)

[Cloudflare](https://1.1.1.2) malware content blocking.

`2606:4700:4700::1112`

## Use Conditional Forwarding

Enable conditional forwarding for Local network `192.168.7.0/16`, with a DHCP server of `192.168.7.1` and a local domain of `bean`.
