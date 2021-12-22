# NGINX

Configure nginx for accept TLS v1.2 and v1.3 and enable support for Perfect Forward Secrecy

## Usage

* Add files .crt and .key into the path `./docker/nginx/ssl/`
* Update server name in `./docker/nginx/config/default.conf`
* Execute `docker-compose up -d`

## Test

Check your domain in https://www.ssllabs.com/ssltest/
