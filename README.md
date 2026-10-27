# Kubernetes Platform on GKE

## Environment
- Cluster: k8s-learning-cluster
- Namespace: app-dev
- Application: Nginx
- Deployment: nginx-web
- Replicas: 3
- Service: nginx-service (ClusterIP)

## Skills Practiced
- Kubernetes Deployments and Services
- EndpointSlices and internal DNS
- Resource requests and limits
- Readiness and liveness probes
- Rolling updates and rollback
- Horizontal Pod Autoscaling
- ConfigMaps and Secrets
- Troubleshooting with kubectl

## Validation
Validate manifests without applying changes:
- kubectl apply --dry-run=client -f k8s/base/nginx-deployment.yaml
- kubectl apply --dry-run=client -f k8s/base/nginx-service.yaml

## Security
Never commit real credentials or secret values to Git.
