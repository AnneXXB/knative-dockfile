### sync image by ali_image-syncer
1. step 0: edit by gitpod
2. step 1: update config.yaml
2. step 2: run command list below
``` shell
wget https://github.com/AliyunContainerService/image-syncer/releases/download/v1.3.0/image-syncer-v1.3.0-linux-amd64.tar.gz
tar -zxf image-syncer-v1.3.0-linux-amd64.tar.gz
./image-syncer --proc=20 --config=config.yaml --retries=3
``` 
> **备注**：
gcloud container images list --repository=k8s.gcr.io/metrics-server
 
> **备注**：
gcloud container images list-tags k8s.gcr.io/metrics-server/metrics-server

