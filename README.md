# python ubl tracker

helm chart is in the helm folder

terraform module in the terraform folder

## build container image

see Dockerfile for specifics, but
```
docker build . -t daveoy/python-ubl-tracker --platform x86_64
```

should do it

### TODO

- ci