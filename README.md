# traefik

 - `sudo apt -y install apache2-utils`
 - `htpasswd -cBb secrets/basic_auth_credentials HTTP_USERNAME HTTP_PASSWORD`
   - Replace HTTP_USERNAME and HTTP_PASSWORD with actual username and password
   - Surround password with single quotes

- Only as needed: `sudo chown root:root /home/ubuntu/docker/traefik/secrets/basic_auth_credentials`
