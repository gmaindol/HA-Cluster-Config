# HA_Cluster_Config
Configuring HA Cluster in PANOS 9.2
# Prerequisite

# Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.








IPv6 Interface configuration skillet provides quick an easy way to configure an IPv6 address on PANOS data plane interfaces. With this skillet customer (enterprise or SP) can configure IPv6 on multiple interfaces and assign them to respective VR (virtual router) and Security Zones.

With this skillet following setting are configured on the interface

Enables IPv6 on the interface
Configures IPv6 address on interface
Virtual Router
Security Zone
Enables NDP monitoring
# Prerequisite
Interface name where IPv6 needs to be enabled
IPv6 address
Name of vrouter that needs to be confiured for this interface
Name of Security Zone that needs to be confiured for this interface
You can provides subnet or host IP as an IPv6 address. When using subnet the host part of the address is derived using the Interface ID. RA are not enabled and needs to configured seperately. You can use exsisting Security Zone and Virtual Router ids, else new value provided in the variable will create a corresponding resource.

# Support Policy
The code and templates in the repo are released under an as-is, best effort, support policy. These scripts should be seen as community supported and Palo Alto Networks will contribute our expertise as and when possible. We do not provide technical support or help in using or troubleshooting the components of the project through our normal support options such as Palo Alto Networks support teams, or ASC (Authorized Support Centers) partners and backline support options. The underlying product used (the VM-Series firewall) by the scripts or templates are still supported, but the support is only for the product functionality and not for help in deploying or using the template or script itself. Unless explicitly tagged, all projects or work posted in our GitHub repository (at https://github.com/PaloAltoNetworks) or sites other than our official Downloads page on https://support.paloaltonetworks.com are provided under the best effort policy.


