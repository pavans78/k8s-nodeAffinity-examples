# k8s-nodeAffinity-examples

This repo contains the examples on the Node Affinity, Node Selector and NodeName. This explains about how the pod will be scheduled into node using the node conditions.

Node affinity is conceptually similar to nodeSelector, allowing you to constrain which nodes your Pod can be scheduled on based on node labels. There are two types of node affinity:

`requiredDuringSchedulingIgnoredDuringExecution`: The scheduler can't schedule the Pod unless the rule is met. This functions like nodeSelector, but with a more expressive syntax.

`preferredDuringSchedulingIgnoredDuringExecution`: The scheduler tries to find a node that meets the rule. If a matching node is not available, the scheduler still schedules the Pod.

For more information on the node affinity please refer this [link](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#node-affinity)


