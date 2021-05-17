## sync image from k8s.gcr.io to dockerhub
Sync k8s.gcr.io docker images to dockerhub use aliyun image-syncer
If you want list repository or image tag, Open google cloudshell  and run:

gcloud container images list --repository=k8s.gcr.io/metrics-server
gcloud container images list-tags k8s.gcr.io/metrics-server/metrics-server
