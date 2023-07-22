# images-Portworx-Essentials
KBVER=1.26.6
PXVER=3.0.0
curl -o px-ag-install.sh -L "https://install.portworx.com/$PXVER/air-gapped?kbver=$KBVER"

  👇

registry.k8s.io/pause:3.1
registry.k8s.io/kube-controller-manager-amd64:v1.26.6
registry.k8s.io/kube-scheduler-amd64:v1.26.6
registry.k8s.io/kube-scheduler-amd64:v1.21.4
registry.k8s.io/sig-storage/csi-node-driver-registrar:v2.6.2
registry.k8s.io/sig-storage/csi-provisioner:v3.3.0
registry.k8s.io/sig-storage/csi-resizer:v1.6.0
registry.k8s.io/sig-storage/csi-snapshotter:v6.1.0
registry.k8s.io/sig-storage/snapshot-controller:v6.1.0
