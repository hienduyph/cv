# hienph's CV


## Run Locally

```bash
podman run --rm -it --volume "$(pwd):/data:Z" --user $(id -u):$(id -g) --userns=keep-id --entrypoint /usr/bin/pdflatex docker.io/texlive/texlive:latest cv.text -o cv.pdf
```
