# Get Latest ECR Image

Query and get latest ECR image of a specific tag and pull it if needed
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
    ecr-repository-name: mychart
    tag-name: "1.0.0"
    chart-path: ./charts/mychart
```