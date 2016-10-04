# docker-dns
Container to resolve container names to IPs

## Usage
`docker run --restart="always" --name docker-dns -d -v /var/run/docker.sock:/var/run/docker.sock -v /etc/hosts:/etc/hosts tsari/docker-dns`