# COEFIT
**Cost-Effective IT Infrastructure**

COEFIT is a framework for designing and deploying IT environments that are:

- **Affordable** – built primarily on open-source and freely available technologies, reducing licensing costs.  
- **Reliable** – based on proven solutions with strong community or enterprise support.  
- **Scalable** – adaptable to small, medium, or large environments without major architectural changes.  
- **Efficient** – minimizing complexity and resource consumption while maintaining functionality.  
- **Automatable** – many components can be deployed and managed using [ezy-install](https://github.com/source-saraiva/ezy-install), reducing time-to-production.  

The goal of COEFIT is to give system administrators, IT managers, and small-to-medium businesses a clear roadmap for building a modern IT infrastructure without overspending.

---


| Server Needs       | Recommendation                                                                                                                                      | Deployable using ezy-install |
|--------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|
| Virtualization     | [Proxmox VE](https://www.proxmox.com/en/products/proxmox-virtual-environment/overview)                                                              | No                           |
| Firewall           |[Opnsense](https://opnsense.org/)                                                                                                                    | No                           |
| VPN                | [Opnsense (openvpn)](https://opnsense.org/)                                                                                                         | No                           |
| Directory          | [Windows Active Directory](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2025?msockid=31e7aedfce22635a0767bb69cff662f3)        | No                           |
| Server OS          | [Rocky Linux](https://rockylinux.org/)                                                                                                              | No                           |
| File Sharing/ Meetings / Chat /Mails     | [Nextcloud Files](https://nextcloud.com/files/)                                                                               | Yes                          |
| Service Desk/ Inventory  | [GLPI](https://glpi-project.org/)                                                                                                             | Yes                          |
| Monitoring         | [Zabbix](https://www.zabbix.com/)                                                                                                                   | Yes                          |
| Patch Management   | [Rudder](https://www.rudder.io/)                                                                                                                    | Yes                          |
| 



| Clients Needs        | Recommendation                                                                                                                                          |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| Office Suite         | [Libre Office](https://www.libreoffice.org/)                                                                                                            |

> *Can be installed using [ezy-install](https://github.com/source-saraiva/ezy-install/) a one-command installation tool
