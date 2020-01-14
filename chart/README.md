tautulli
========
Tautulli integrates with Plex to provide you a feature-rich dashboard of statistics from user activity to a graphical history of streams, play count, along with configurable notifications, and more.

Current chart version is `0.1.2`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| chownDataImage.pullPolicy | string | `"IfNotPresent"` |  |
| chownDataImage.repository | string | `"busybox"` |  |
| chownDataImage.tag | string | `"1.30.0"` |  |
| fullnameOverride | string | `""` |  |
| getGeoCity.enabled | bool | `false` |  |
| getGeoCity.image.pullPolicy | string | `"IfNotPresent"` |  |
| getGeoCity.image.repository | string | `"busybox"` |  |
| getGeoCity.image.tag | string | `"1.30.0"` |  |
| image.pullPolicy | string | `"Always"` |  |
| image.repository | string | `"tautulli/tautulli"` |  |
| image.tag | string | `"latest"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0] | string | `"chart-example.local"` |  |
| ingress.paths[0] | string | `"/"` |  |
| ingress.tls | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| persistence.accessModes[0] | string | `"ReadWriteOnce"` |  |
| persistence.enabled | bool | `true` |  |
| persistence.size | string | `"1Gi"` |  |
| persistence.storageClassName | string | `""` |  |
| podAnnotations | object | `{}` |  |
| replicaCount | int | `1` |  |
| resources | object | `{}` |  |
| service.port | int | `8181` |  |
| service.type | string | `"ClusterIP"` |  |
| tautulli.gid | int | `1000` |  |
| tautulli.tz | string | `"UTC"` |  |
| tautulli.uid | int | `1000` |  |
| tolerations | list | `[]` |  |
