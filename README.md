# adrian-marcu.github.io
Personal site


https://community.cloudflare.com/t/github-pages-keep-saying-it-cant-enforce-https/397570

DNS SSL Certificate fix:
1. Grey out Proxy status  to "DNS only"
2. Use the less-secure Full (non-strict) SSL mode which allows Cloudflare to continue trusting the expired certificate (insecure).
3. Put everything back again every 3 months
