### Get docker image
``bash
docker pull tensorflow/tensorflow:2.0.0-py3-jupyter
```
### Start Tensorflow
```bash
 docker run -d \
    --name=tensorflow \
    -p 8888:8888 \
    tensorflow/tensorflow:2.0.0-py3-jupyter
```

### Copy your notebooks
```bash
docker cp labs tensorflow:/tf/
```