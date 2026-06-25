# Ceph Cluster Validation Commands

This document contains basic commands used to validate the health and status of the Ceph cluster.

---

## Cluster Status
ceph -s


## Display OSD
ceph osd tree


## Shows Storage Usage Per Pool
ceph df


## Provides Detailed Health Wanings
ceph health detail



## Notes
These commands are used for daily monitoring and troubleshooting of Ceph clusters in production or lab environments.
