# Amena Horizontal Pod Scale
## amena-web-backend
> CPUAverageUtilization >= 70% → Scale Up

[Manifest](https://github.com/amena-dev/amena-web-backend/blob/master/k8s/amena-web-backend.yml)


## amena-web-frontend
> CPUAverageUtilization >= 70% → Scale Up

[Manifest](https://github.com/amena-dev/amena-web-frontend/blob/master/k8s/amena-web-frontend.yml)

## amena-3dp-engine
> Pod Count = SQS Queue Size

[By Custmized KEDA](https://github.com/amena-dev/keda)

[Manifest](https://github.com/amena-dev/amena-3dp-engine/blob/main/k8s/amena-3dp-engine.yml)