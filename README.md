# hackathon-smartbox-site

docker-compose up -d

docker exec hackathon-smartbox-site-php-fpm compose install

docker exec hackathon-smartbox-site-php-fpm ./vendor/bin/jigsaw build

./vendor/bin/jigsaw serve --port=8087
