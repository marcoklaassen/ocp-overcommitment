# OCP CPU Overcommitment

Have a look at: https://docs.openshift.com/container-platform/4.9/nodes/clusters/nodes-cluster-overcommit.html

* `oc label machineconfigpool worker custom-kubelet=small-pods `
* `oc apply -f disable-cpu-limit.yaml`
