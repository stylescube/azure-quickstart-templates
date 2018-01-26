# Arista vEOS Router

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Farista-veos-router-4-nic-ha%2Fazuredeploy.json" target="_blank">
<img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Farista-veos-router-4-nic-ha%2Fazuredeploy.json" target="_blank">
<img src="http://armviz.io/visualizebutton.png"/>
</a>

The Arista vEOS Router is a cloud-grade, featurerich, multi-cloud and multi-hypervisor virtual router that empowers enterprises and cloud providers to build consistent, highly secure and scalable hybrid cloud networks. Already proven in the most demanding public cloud infrastructures, Arista vEOS Router extends the Arista EOS platform from Arista’s award-winning physical switching and routing platforms into the virtualized environment. The Arista vEOS Router delivers an Any Cloud gateway, plus public cloud routing services and network services for virtualized customer environments and more. 

This deployment creates vEOS Router with 4 NICs. Route Tables for the subnets are configured with the vEOS Router as the gateway for all traffic outside of the private subnet. A reserved subnet is created for the vEOS Router instances. Additionally, two vEOS Routers are installed to provide High-Availability, and all non-reserved subnets are assigned to one of the routers through User Defined Routes.

`Tags: Arista, EOS, vEOS, Router`
