# vaccsedu.org

Serves vaccsedu.org through GitHub Pages and redirects every page to
https://stevenmcarr.github.io/vaccs/. `404.html` is the same redirect, so old
links such as vaccsedu.org/irvis also land on the VACCS page.

DNS (Namecheap, Advanced DNS): four A records for `@` pointing to
185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, and a
CNAME record for `www` pointing to `stevenmcarr.github.io.`. Keep the MX
records for email.
