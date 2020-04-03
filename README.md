# illallangi-alfa

Manages Illallangi's alfa network services, consisting of various Kubernetes clusters.

## kubernetes play

  - [kubernetes]
    - [k8s]
     - [docker]
       - [docker-ce]
         - [docker-ce-cli]
           - [docker-repository]
             - [package-manager]
               - [software-properties-common]
               - [gnupg2]
               - [curl]
               - [ca-certificates]
               - [apt-transport-https]
         - [docker-repository]
           - [package-manager]
             - [software-properties-common]
             - [gnupg2]
             - [curl]
             - [ca-certificates]
             - [apt-transport-https]
       - [containerd]
         - [docker-repository]
           - [package-manager]
             - [software-properties-common]
             - [gnupg2]
             - [curl]
             - [ca-certificates]
             - [apt-transport-https]
     - [iptables-legacy]
     - [iptables-bridged-traffic]
       - [br-netfilter]
       - [procps]
     - [lobalancer]
       - [ospf]
       - [lsof]
     - [kubernetes-cni]
     - [kubelet]
       - [kubernetes-repository]
         - [package-manager]
           - [software-properties-common]
           - [gnupg2]
           - [curl]
           - [ca-certificates]
           - [apt-transport-https]
     - [kubectl]
       - [kubernetes-repository]
         - [package-manager]
           - [software-properties-common]
           - [gnupg2]
           - [curl]
           - [ca-certificates]
           - [apt-transport-https]
       - [bash-completion]
     - [kubeadm]
       - [kubernetes-repository]
         - [package-manager]
           - [software-properties-common]
           - [gnupg2]
           - [curl]
           - [ca-certificates]
           - [apt-transport-https]
  - [nfs]
  - [hosts]
  - [hostname]

## Hosts

| Host      | IP Address     | Use                     | Model                               | CPU                                | Cores | Frequency | RAM   | Ethernet           | Wireless           |
|-----------|----------------|-------------------------|-------------------------------------|------------------------------------|-------|-----------|-------|:------------------:|:------------------:|
| mel-heo-1 | 172.20.227.196 | Master, Worker, Storage | White Box                           | [Intel(R) Core(TM) i7-960][i7-960] | 4     | 3.2GHz    | 24GB  | :heavy_check_mark: | :x:                |
| mel-heo-2 | 172.20.227.197 | Master, Worker, Storage | White Box                           | [Intel(R) Core(TM) i7-960][i7-960] | 4     | 3.2GHz    | 36GB  | :heavy_check_mark: | :x:                |
| mel-heo-3 | 172.20.227.198 | Master, Worker, Storage | White Box                           | [Intel(R) Core(TM) i7-960][i7-960] | 4     | 3.2GHz    | 36GB  | :heavy_check_mark: | :x:                |
| mel-rpi-1 | 172.20.227.199 | Edge                    | Raspberry Pi 4 Model B Rev 1.1      | [Cortex-A72][cortex-a72]           | 4     | 1.5 GHz   | 4GB   | :heavy_check_mark: | :heavy_check_mark: |
| mel-rpi-2 | 172.20.227.200 | Edge                    | Raspberry Pi 4 Model B Rev 1.1      | [Cortex-A72][cortex-a72]           | 4     | 1.5 GHz   | 4GB   | :heavy_check_mark: | :heavy_check_mark: |
| mel-rpi-3 | 172.20.227.201 | Edge                    | Raspberry Pi 4 Model B Rev 1.1      | [Cortex-A72][cortex-a72]           | 4     | 1.5 GHz   | 4GB   | :heavy_check_mark: | :heavy_check_mark: |
| mel-rpi-4 | 172.20.227.202 | Edge                    | Raspberry Pi 4 Model B Rev 1.1      | [Cortex-A72][cortex-a72]           | 4     | 1.5 GHz   | 4GB   | :heavy_check_mark: | :heavy_check_mark: |
| mel-rpi-5 | 172.20.227.203 | Edge                    | Raspberry Pi 4 Model B Rev 1.1      | [Cortex-A72][cortex-a72]           | 4     | 1.5 GHz   | 4GB   | :heavy_check_mark: | :heavy_check_mark: |
| mel-rpi-6 | 172.20.227.204 | Edge                    | Raspberry Pi 4 Model B Rev 1.1      | [Cortex-A72][cortex-a72]           | 4     | 1.5 GHz   | 4GB   | :heavy_check_mark: | :heavy_check_mark: |
| mel-rpi-7 | 172.20.227.205 | Edge                    | Raspberry Pi 3                      |
| mel-rpi-8 | 172.20.227.206 | Edge                    | Raspberry Pi 3                      |
| mel-nuc-1 | 172.20.227.207 | Worker                  | Intel NUC                           |
| mel-nuc-2 | 172.20.227.208 | Worker                  | Intel NUC                           |
| mel-nuc-3 | 172.20.227.209 | Worker                  | Intel NUC                           |
| mel-nuc-4 | 172.20.227.210 | Worker                  | Intel NUC                           |


[ca-certificates]: https://github.com/illallangi-alfa/configure-ca-certificates
[cgroup]: https://github.com/illallangi-alfa/configure-cgroup
[containerd]: https://github.com/illallangi-alfa/configure-containerd
[curl]: https://github.com/illallangi-alfa/configure-curl
[device-mapper-persistent-data]: https://github.com/illallangi-alfa/configure-device-mapper-persistent-data
[docker-ce-cli]: https://github.com/illallangi-alfa/configure-docker-ce-cli
[docker-ce]: https://github.com/illallangi-alfa/configure-docker-ce
[docker-repository]: https://github.com/illallangi-alfa/configure-docker-repository
[docker]: https://github.com/illallangi-alfa/configure-docker
[firewalld]: https://github.com/illallangi-alfa/configure-firewalld
[gnupg2]: https://github.com/illallangi-alfa/configure-gnupg2
[hostname]: https://github.com/illallangi-alfa/configure-hostname
[hosts]: https://github.com/illallangi-alfa/configure-hosts
[iptables-legacy]: https://github.com/illallangi-alfa/configure-iptables-legacy
[k8s]: https://github.com/illallangi-alfa/configure-k8s
[kubeadm]: https://github.com/illallangi-alfa/configure-kubeadm
[kubectl]: https://github.com/illallangi-alfa/configure-kubectl
[kubelet]: https://github.com/illallangi-alfa/configure-kubelet
[kubernetes-cni]: https://github.com/illallangi-alfa/configure-kubernetes-cni
[kubernetes-repository]: https://github.com/illallangi-alfa/configure-kubernetes-repository
[kubernetes]: https://github.com/illallangi-alfa/configure-kubernetes
[lobalancer]: https://github.com/illallangi-alfa/configure-lobalancer
[lsof]: https://github.com/illallangi-alfa/configure-lsof
[lvm2]: https://github.com/illallangi-alfa/configure-lvm2
[ospf]: https://github.com/illallangi-alfa/configure-ospf
[package-manager]: https://github.com/illallangi-alfa/configure-package-manager
[python3-openshift]: https://github.com/illallangi-alfa/configure-python3-openshift
[selinux]: https://github.com/illallangi-alfa/configure-selinux
[software-properties-common]: https://github.com/illallangi-alfa/configure-software-properties-common
[cortex-a53]: https://developer.arm.com/ip-products/processors/cortex-a/cortex-a53
[cortex-a72]: https://developer.arm.com/ip-products/processors/cortex-a/cortex-a72
[cortex-a7]: https://developer.arm.com/ip-products/processors/cortex-a/cortex-a7
[i7-960]: https://ark.intel.com/content/www/us/en/ark/products/37151/intel-core-i7-960-processor-8m-cache-3-20-ghz-4-80-gt-s-intel-qpi.html
