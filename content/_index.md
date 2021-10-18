---
title: "AS4242422331"
date: 2021-10-15T12:52:20Z
---
# AS4242422331

## Peering Policy

All nodes are open for peering ( only support `Wireguard` ), you can find me from the [DN42 Group Chat (unofficial)](https://t.me/Dn42Chat) in Telegram.

I prefer `multiprotocol` BGP sessions over IPv6. For WireGuard + BIRD users, I recommend using `link-local` IPv6 addresses, and enable the `extended next hop` option for IPv4.

## Nodes
|Domain|Clearnet IPv6|Location|Wireguard Pubkey|DN42 IPv4|DN42 IPv6|Link-Local IPv6|
|------|-------------|--------|----------------|---------|---------|---------------|
|tw201.dn42.williamgates.info|no|Taipei|D9O5wPiRVFUAZzqVJlfpNONAEEy/Ljj8vw5L6PXUpBo=|172.23.131.201|fd62:c9e2:af95:201::1|fe80::2331| 
|sg206.dn42.williamgates.info|yes|Singapore|I5yRgHFY+qfkRwT6UpVBsUIiA5hmEOv1cU2licfrokw=|172.23.131.206|fd62:c9e2:af95:206::1|fe80::2331|
|cz207.dn42.williamgates.info|yes|Prague|22Yg+PozQDDJUufe2POaV/ron0wZ6LVznpMgrRZDAXI=|172.23.131.207|fd62:c9e2:af95:207::1|fe80::2331|

```
define last5 = int(last 5 digits of your ASN);
if last5 < 50000 then my_wireguard_port = last5;
else my_wireguard_port = 30000 + int(last 4 digits of your ASN);
```



