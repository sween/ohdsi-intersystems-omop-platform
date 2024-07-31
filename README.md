# OHDSI Chart for InterSystems OMOP Platform 
Helm chart for deploying OHDSI ATLAS and WebAPI with the InterSystems OMOP Platform

> Under Heavy Development

Repo
```sh
helm repo add sween https://sween.github.io/ohdsi-intersystems-omop-platform
helm repo update
```

Install
```sh
helm install ohdsi oci://ghcr.io/sween/ohdsi-intersystems-omop-platform/ohdsi --create-namespace -n isc
```

Update
```sh

```