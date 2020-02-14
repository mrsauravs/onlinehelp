---
title: Configure DoH through configuration panel
category: DNS-over-HTTPS
order: 2
---

If you use Mozilla Firefox, you can configure DNS-over-HTTPS (DoH) through the configuration panel.

Follow these steps:

1. In the address bar, type *about:config*.
2. Search for *network.ttr.mode* and set any of the following values:
    - 2: Turns on DoH and keeps the regular DNS only as a backup.
    - 3: Turns on DoH with no regular DNS support.
3. Search for *network.ttr.uri* and set the domain name of the DNS resolver.
    - The default Cloudfare URI is https://mozilla.cloudflare-dns.com/dns-query
4. (Optional.) Search for *network.ttr.bootstrapAddress* and set the IP address.
    - Type *1.1.1.1* for Cloudfare.
    - Type *8.8.8.8* for Google.

