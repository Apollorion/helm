# Welcome to my helm repo

I drop all my helm charts for all my projects here.

## Using this repo

1. `helm repo add apollorion https://apollorion.github.io/helm/`
2. HUZZAH

## Contributing to this repo

1. Build your helm chart package `helm package ./`
2. Add the `.tgz` file to the root of this repository
3. $$$ PROFIT $$$ - Github CI will automatically regenerate index.yaml for use!!

## Projects Published Here

[HomeDyDNS](https://github.com/Apollorion/homedydns) - A solution for dynamic dns that runs in k8s and updates route53