# Para configurar el host y que use lima se debe ejecutar los siguientes comandos
```
docker context create lima --docker "host=unix://${HOME}/.lima/docker/sock/docker.sock"
docker context use lima
docker run hello-world
```
# Para iniciar el contexto de lima
`limactl start docker.yaml`

# Para detener el contexto de lima
`limactl stop docker`