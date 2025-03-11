# traefik

`sudo apt -y install apache2-utils`
`sudo htpasswd -cBb /home/ubuntu/docker/traefik/secrets/basic_auth_credentials HTTP_USERNAME HTTP_PASSWORD`
Replace HTTP_USERNAME and HTTP_PASSWORD with actual username and password

`sudo chown root:root /home/ubuntu/docker/traefik/secrets/basic_auth_credentials`
