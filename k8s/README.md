## Kong Helm Charts
```
$ helm repo add kong https://charts.konghq.com
$ helm repo update

# Helm 3
$ helm install -f kong/values.yaml kong kong/kong
```

## Konga Helm Charts
helm install kong ./konga/

Kong Admin URL: http://kong-kong-admin:8001