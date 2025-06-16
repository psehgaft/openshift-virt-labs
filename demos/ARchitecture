# Demo Environment Preparation

---

## Example Infrastructure

### Minikube/Kind + KubeVirt

- **Minikube/Kind**
- Lightweight Kubernetes clusters for local testing
- Run multiple nodes on a single machine
- **KubeVirt**
- Adds VM management to Kubernetes
- Leverages CRDs: `VirtualMachine`, `VirtualMachineInstance`
- **Audiovisual Aid:**
![Minikube + KubeVirt Architecture](https://kubevirt.io/user-guide/assets/architecture-simple.png)
_Diagram courtesy of the KubeVirt User Guide_

---

## Prerequisites

- **ISO Images**
- Fedora CoreOS or CentOS Stream QCOW2/ISO
- Download from official releases
- **Test Disks**
- Sample QCOW2 guest disks for proof-of-concept
- **CLI Tools**
- `kubectl` / `oc`
- `virtctl` (KubeVirt CLI)
- `docker` or `podman` (for local registries)
- **Kubeconfig**
- Access to your Kubernetes cluster context
- **Audiovisual Aid:**
![Prerequisites Checklist](https://kubevirt.io)
_Screenshot from KubeVirt Quickstart_

---

## Quick Operator Deployment

1. **Add KubeVirt Repository**
 ```bash
 kubectl apply -f https://github.com/psehgaft/openshift-virt-labs/blob/master/configs/kubevirt-operator.yaml
 ```
2. **Deploy KubeVirt CR**
 ```bash
 kubectl apply -f https://github.com/psehgaft/openshift-virt-labs/blob/master/configs/kubevirt-cr.yaml
 ```
3. **Verify Installation**
 ```bash
 kubectl -n kubevirt get pods
 ```
4. **Audiovisual Aid:**
 - Short GIF: CLI installation flow
 - Reference video: https://www.youtube.com/watch?v=example_kubevirt_install

---
