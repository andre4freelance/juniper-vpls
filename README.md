# JUNIPER VPLS

This repository provides configuration examples for **Juniper VPLS (Virtual Private LAN Service)** running on **Juniper vMX**.
The scenario simulates a Provider network where **OSPF**, **MPLS**, **LDP**, and **BGP** form the underlay. On top of this, **RO-SITE-A** and **RO-SITE-B** are connected over **VLAN100**, effectively bridging them across the MPLS backbone as if they were on the same local segment.

As an additional note, this lab was migrated from **vQFX** to **vMX** to resolve simulation limitations and ensure proper control plane behavior.

---

## Topology

![Topology](images/1.topology.png)

---

## Testing

The status verification confirms that VPLS, BGP, MPLS, and LDP are functioning correctly.
![VPLS Status](images/2.VPLS-status.png)

The connectivity test shows successful ping responses between the two remote sites.
![Ping Test](images/3.ping-from-SITE-A-to-SITE-B.png)

---

## Devices

- **RO**: MikroTik RouterOS 7.14.3
- **JUNIPER**: Juniper vMX-v14.1R1.10

---

## Links

Origin : 
<https://github.com/andre4freelance/juniper-vpls>

Linkedin post : 
<https://www.linkedin.com/posts/link-andre-bastian_networking-junipernetworks-vpls-activity-7361487051986231300-Ga8c?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD73JlUBty-p-mBfMEW0-O4j0sv-e_PRQvc>

Facebook post : 
<https://www.facebook.com/share/p/17nXEArUVm/>