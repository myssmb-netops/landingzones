# blueprint_networking_shared_services
blueprint_networking_shared_services brings the foundation of shared services (hub) network in a hub-spoke topology. <br/>

# Overall architecture
The following diagram shows the environment we are deploying in this blueprint: 
![Shared](https://github.com/aztfmod/landingzones/blob/master/landingzone_vdc_demo/docs/diagram-shared.png)


## Capabilities

 - Virtual network
    - Virtual network address space
    - DNS Servers 
    - Subnets
        - Subnet address space
        - Network Security Groups 
        - Virtual Network Service Endpoints
        - NSG diagnostics
    - Attach NSG to subnet
    - Virtual network operations logs and auditing
 - DDoS Protection plan standard
 - Azure Bastion Host (GA in some regions only)


# Contribute
This is a demo environement but pull requests are welcome to evolve the framework and integrate new features!