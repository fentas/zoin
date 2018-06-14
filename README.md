# zoin

```sh
docker run -d --name zoin --net=host --env="DISPLAY" --privileged \
  -v "$HOME/.Xauthority:/root/.Xauthority:rw" \
  -v "$HOME/.zoin:/root/zoin:rw"
  fentas/zoin:latest
