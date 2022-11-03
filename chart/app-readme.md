# Prehook Test
## Prereqs

The following prerequisites can be accessed/installed through the Rancher app catalog.

| Name | Required | Notes|
|---|---|---|
| CIS Benchmark | Yes | If utilizing Alerting, required to set the '.alert.enabled' to true in the Benchmark app values/configuration |
| Rancher Monitoring | No | Required if utilizing Alerting |

***NOTE***: The installation will fail if the above prerequisites do not exist. Check the `preinstall-hook` pod in the namespace for logs. If the install fails due to prereqs, uninstall this chart, install the prereqs, and try again.