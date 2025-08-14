### Docker Compose for Rancher 2.0

Install Rancher with the docker-compose.yaml in this project with the following command

```docker-compose up -d```

OR

docker run -d --restart=unless-stopped --name rancher --hostname rancher --privileged -p 80:80 -p 443:443 rancher/rancher:latest`

### Kubernetes DNS

This can be a handy way to add DNS entries into the Kubernetes DNS:

[https://coredns.io/2017/05/08/custom-dns-entries-for-kubernetes/](https://coredns.io/2017/05/08/custom-dns-entries-for-kubernetes/)
