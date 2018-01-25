# Let's Encrypt Set Up

```
sudo git clone https://github.com/letsencrypt/letsencrypt /opt/letsencrypt
cd /opt/letsencrypt
./letsencrypt-auto certonly -a webroot --webroot-path=/usr/share/nginx/html -d gowilbur.com -d www.gowilbur.com
```

See full instructions on [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-secure-nginx-with-let-s-encrypt-on-ubuntu-14-04)
