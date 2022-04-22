# nginx

```
nginx -t
service nginx restart
sudo apt install certbot python3-certbot-nginx
sudo ufw allow 'Nginx Full'
sudo ufw delete allow 'Nginx HTTP'
```

```
sudo certbot --nginx -d domain.com
```
or
```
sudo certbot --nginx -d domain.com -d www.domain.com
```
