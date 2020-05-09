# Varnish-WP

Varnish configuration for Wordpress & CMS

## Step use

- Edit config XXX.XXX.XXX.XXX repeat by you IP backend web server.
- Edit port by you port backend web server
- check firewall for allow listen backend & proxy

### for Plesk

- Install Varnish by Docker follow thid link.
  https://www.plesk.com/blog/product-technology/varnish-wordpress-docker-container/
- or edit file docker in /etc/varnish/default.vcl
- use config default.vcl in this git.
- Allow firewall port for Varnish to Apache HTTP:7080, HTTPS:7081
