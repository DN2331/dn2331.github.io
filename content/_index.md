---
title: "AS4242422331"
date: 2021-10-15T12:52:20Z
---
# AS4242422331

## Peering Policy

All nodes are open for peering ( only support `Wireguard` ), you can find me from the [DN42 Group Chat (unofficial)](https://t.me/Dn42Chat) in Telegram. You can also [Email](mailto:dn2331@williamgates.info) me.

I prefer `multiprotocol` BGP sessions over IPv6. For WireGuard + BIRD users, I recommend using `link-local` IPv6 addresses, and enable the `extended next hop` option for IPv4.

## Nodes

##### 201

```yaml
Location: Taipei
Clearnet domain: Send me Email to get the domain info (IPv4 only) 
Wireguard pubkey: D9O5wPiRVFUAZzqVJlfpNONAEEy/Ljj8vw5L6PXUpBo=
DN42 IPv4: 172.23.131.201
DN42 IPv6: fd62:c9e2:af95:201::1
Link-local IPv6: fe80::2331/64
```

##### 206

```yaml
Location: Singapore
Clearnet domain: Send me Email to get the domain info (IPv4/IPv6)
Wireguard pubkey: I5yRgHFY+qfkRwT6UpVBsUIiA5hmEOv1cU2licfrokw=
DN42 IPv4: 172.23.131.206
DN42 IPv6: fd62:c9e2:af95:206::1
Link-local IPv6: fe80::2331/64
```

##### 207

```yaml
Location: Prague
Clearnet domain: Send me Email to get the domain info (IPv4/IPv6)
Wireguard pubkey: 22Yg+PozQDDJUufe2POaV/ron0wZ6LVznpMgrRZDAXI=
DN42 IPv4: 172.23.131.207
DN42 IPv6: fd62:c9e2:af95:207::1
Link-local IPv6: fe80::2331/64
```
##### 208
```yaml
Location: Luxembourg
Clearnet domain: Send me Email to get the domain info (IPv4/IPv6)
Wireguard pubkey: c4AZZVNUzXCASWG96CKUpY+gQLdGwA1rbqkYCHXnW10=
DN42 IPv4: 172.23.131.208
DN42 IPv6: fd62:c9e2:af95:208::1
Link-local IPv6: fe80::2331/64
```

##### 209
```yaml
Location: Chisinau
Clearnet domain: Send me Email to get the domain info (IPv4/IPv6)
Wireguard pubkey: 09NtkFC0eK5mYUkL9jpJ3zv1sTeMyVWdVymZ5L17Mmc=
DN42 IPv4: 172.23.131.209
DN42 IPv6: fd62:c9e2:af95:209::1
Link-local IPv6: fe80::2331/64
```

## Wireguard port on my side

```clike
if int(last_5_digits_of_your_ASN) < 50000 then {
	my_wireguard_port = int(last_5_digits_of_your_ASN);
};
else {
	my_wireguard_port = 30000 + int(last_4_digits_of_your_ASN);
};
```

