# Package Helm ECR Action

Package a helm chart and deploy to an AWS ECR repository using OCI
<!-- ## Inputs

| Input | Type | Description | Default | Required
| ------ | ------ | ------ | ------ | ------
| install_local_cluster | Boolean (String) | Install a local K3d Cluster | true | Yes -->

## Full Example usage

```yaml
- name: Package and Push a Helm Chart to AWS
  uses: explorium-ai/package-helm-ecr-action@main
  with:
    aws-access-key-id: fadsfads********
    aws-secret-access-key: fadsfads********
    aws-region: eu-west-1
    ecr-repo-name: mychart
    chart-path: ./charts/mychart
```