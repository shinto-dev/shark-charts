# shark-charts
This is a generic chart which can be used for deploying any application.



To install,
```
helm repo add shark-charts https://shinto-dev.github.io/shark-charts
helm install <release-name> shark-charts/shark-charts [-f custom-values.yaml]
```

[Chart-releaser](https://github.com/helm/chart-releaser) is used for making the github repository as helm repository. Follow this [link](https://tech.paulcz.net/blog/creating-a-helm-chart-monorepo-part-1/) for more.
