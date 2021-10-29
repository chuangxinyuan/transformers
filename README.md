# KFServing MASK RCNN

This is a proof-of-concept imitation of a MASK RCNN model using tensorflow, implemented using kfserving.

The inspiration comes from CVAT's nuclio model

https://github.com/openvinotoolkit/cvat/tree/develop/serverless/tensorflow/matterport/mask_rcnn/nuclio

## Building kerasserver
Using docker, run

```bash
docker build -t <some-name:some-tag> . -f keras.Dockerfile 
```