# Easy-ssl

## 1- Installation

```
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:certbot/certbot
sudo apt-get update
sudo apt-get install certbot 
sudo certbot certonly --standalone -d YOURDOMAIN -d YOURDOMAIN
```

## 2- when you want to renew

```
sudo certbot renew
```

## 3- now check easy-nginx

## 4- when you want to revoke your cert for a server

```
sudo letsencrypt revoke -d example.com --cert-path /etc/letsencrypt/live/examplecom/cert.pem
```
