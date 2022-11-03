# Prehook Test

Prehook Test for Rancher. Be sure to install the prerequisite charts below from the Rancher app store.

**Prereqs**:
* CIS Benchmark (Required)
* Rancher Monitoring (Optional, required for Alerting)

**NOTE**: The installation will fail if the above prerequisites do not exist. Check the `preinstall-hook` pod in the namespace for logs. If the install fails due to prereqs, uninstall this chart, install the prereqs, and try again.