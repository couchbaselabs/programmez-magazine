# programmez-magazine
Couchbase Autonomous Operator YAML files used in the article for Programmez magazine.

# notes
Of course you need to allocate sufficient resources for your Kubernetes/OpenShift cluster to fit CPU/RAM resources requests in the YAML files.
This is especially true for the final `couchbase-all.yaml` file where both resource types are set with medium/high values for all service types.

