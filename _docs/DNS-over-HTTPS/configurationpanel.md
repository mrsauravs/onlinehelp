---
title: DNS-over-HTTPS
category: Configure DoH through configuration panel
order: 2
---

If you use Mozilla Firefox, you can configure DNS-over-HTTPS (DoH) through the configuration panel.

Follow these steps:

1. Type about:config in the URL bar.
2. In the search area, type network.ttr.mode and set any of the following values:
    - 2: Turns on DoH and keeps the regular DNS only as a backup.
    - 3: Turns on DoH with no regular DNS support.
3. In the search area, type network.ttr.uri to set the domain name of the DNS resolver.
    - The default Cloudfare URI is https://mozilla.cloudflare-dns.com/dns-query
4. (Optional.) In the search area, type network.ttr.bootstrapAddress to set up IP address.
    - Type 1.1.1.1 for Cloudfare.
    - Type 8.8.8.8 for Google.


<!--![](//placehold.it/800x600)--!>
