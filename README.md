# ipsec-skillet
IKE Gateway and IPSEC configuration for Palo Alto Networks Next-Generation FWs


Networking Prerequisites:
 - Local Interface (layer3) configured
 - Zones configured (local and tunnel)
 - Security policy allowing traffic between local zone and tunnel zone
 - Virtual Router with default route through local interface 


Recommended [Generator](https://cloud.google.com/network-connectivity/docs/vpn/how-to/generating-pre-shared-key) for Preshared Key (IKE Gateway)