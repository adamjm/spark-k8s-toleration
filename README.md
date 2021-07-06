# spark-k8s-toleration
A simple guide on how to user tolerations and node selectors with Pyspark on K8s

## Providing Tolerations and Nodeselectors to Spark Pods
Tolerations and node selectors are provided through pod templates. In this repo and example of such a set of tolerations and node selectors are provided for the circumstance where the nodes are tainted because they are IBM Power systems and the appropriate image architecture is required. 


