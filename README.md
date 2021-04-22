# knodepods

`knodepods` lists pods grouped by node in a multi-node Kubernetes cluster.

## Example usage

```
$ knodepods
ip-10-0-2-246.us-west-2.compute.internal:
NAMESPACE    NAME                                                    READY  STATE    RESTART  AGE
kube-system  asg-controller-aws-cluster-autoscaler-65b685c8b4-l8hfh  1      Running  1        2021-04-22T10:37:52Z
kube-system  aws-node-d8fg9                                          1      Running  0        2021-04-22T10:37:15Z
kube-system  coredns-6548845887-7g9q2                                1      Running  0        2021-04-22T10:38:02Z
kube-system  kube-proxy-ptgts                                        1      Running  0        2021-04-22T10:37:15Z

ip-10-0-3-159.us-west-2.compute.internal:
NAMESPACE    NAME                      READY  STATE    RESTART  AGE
kube-system  aws-node-wm8sv            1      Running  0        2021-04-22T10:37:28Z
kube-system  coredns-6548845887-pzl98  1      Running  0        2021-04-22T10:38:02Z
kube-system  kube-proxy-xbm58          1      Running  0        2021-04-22T10:37:28Z
```
