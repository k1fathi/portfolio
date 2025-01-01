docker-compose up -d

docker-compose run --rm certbot certonly --webroot --webroot-path /var/www/certbot -d your-domain.com -d www.your-domain.com

docker compose run --rm certbot certonly --webroot --webroot-path /var/www/certbot --email vibte740@gmail.com --agree-tos --no-eff-email --force-renewal -d vibte.xyz