## How it works
#### webpage
- index.html contains the code for the static page
-   goes inside `/var/www/example.com/html/`
#### nginx
- example.com file contains Nginx configuration
-   goes inside `/etc/nginx/sites-available/`
-   has syslink to `/etc/nginx/sites-enabled/`
#### https
- site is configured to use Cloudflare
- Nginx config contains SSL certifications & index.html paths
