# Build Ansible
## Build
```
docker build -t "test" . --build-arg ssh_prv_key="$(cat ~/.ssh/gcp| base64 )"
```
## Run
```
docker run --name test --rm -i -t ansible bash
```