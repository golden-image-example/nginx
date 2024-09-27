# nginx

```
podman build -f ./1.22/Containerfile .
```

```
oc new-project golden-image-example | oc project golden-image-example
oc create -f ./tekton/pipeline.yaml -n golden-image-example
```