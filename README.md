# vaccsedu.org

Serves vaccsedu.org through GitHub Pages and redirects it to
https://stevenmcarr.github.io/vaccs/. vaccsedu.org/irvis, /eevis and /scvis go
to that tool's install page (`irvis-install.html` and so on). `404.html` sends
any other old link to the matching install page when its first path segment
names a tool (for example /irvis/login), and to the VACCS page otherwise.

DNS (Namecheap, Advanced DNS): four A records for `@` pointing to
185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, and a
CNAME record for `www` pointing to `stevenmcarr.github.io.`. Keep the MX
records for email.
