# Kubernetes CSI Storage Drivers

## Whast is this?
This repo wants to hold a list of Kubernetes CSI drivers and management solution for databases.  
At present the list considers:
- block storage
- distributed block storage
- snapshot & backup/restore capabilities
- UI, CLI and REST interfaces
- *dulcis in fundo*: performance :-)

## In an ideal world
I'd like to stress-test them all with a consistent series of tests and data use-cases and compare them. In practise I know it'll be impossible to test them all and follow them as they mature and new releases come to market.
The idea is to have subdirectories with their names and within it, architecture details with reports on their UX, performance and management capabilities.

### The list
- [Arrikto Rok](https://www.arrikto.com/rok-data-management/)
- [Blockbridge](http://www.blockbridge.com/)
- [Ceph CSI](https://github.com/ceph/ceph-csi)
  - [Ceph FS](https://docs.ceph.com/en/latest/cephfs/)
- [Dell EMC](https://dell.github.io/storage-plugin-docs/)
  - [CSI driver for PowerFlex](https://dell.github.io/storage-plugin-docs/docs/installation/helm/powerflex/)
  - [CSI driver for PowerScale](https://dell.github.io/storage-plugin-docs/docs/installation/helm/isilon/)
  - [CSI driver for PowerMax](https://dell.github.io/storage-plugin-docs/docs/installation/helm/powermax/)
  - [CSI driver for PowerStore](https://dell.github.io/storage-plugin-docs/docs/installation/helm/powerstore/)
  - [CSI driver for Unity](https://dell.github.io/storage-plugin-docs/docs/installation/helm/unity/)
- [Hedvig](https://www.commvault.com/software-defined-storage)
- [Mayadata Kubera](https://mayadata.io/product)
- [NetApp Trident](https://netapp-trident.readthedocs.io/en/stable-v21.01/)
- [OpenEBS](https://openebs.io/)
- [Pure Storage - Portworx](https://portworx.com/)
- [Rancher Labs Longhorn](https://longhorn.io/)
- [Robin](https://robin.io/)
- [Rook](https://rook.io/)
- [StorageOS](https://storageos.com/features)
- [Virtuozzo](https://www.virtuozzo.com/)
 
 

## What a report says

![GigaOm 2020 K8s storage radar](assets/GigaOm_Radar_for_Data_Storage_for_Kubernetes-2020.png)


The actual GigaOm 2020 report
- [link 1](https://containers.robin.io/hubfs/White_Papers/gigaom-radar-for-data-storage-for-kubernetes.pdf)
- [link 2](assets/gigaom-radar-for-data-storage-for-kubernetes-2020.pdf)
