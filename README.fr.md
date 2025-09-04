[![en](https://img.shields.io/badge/lang-en-orange.svg)](https://github.com/source-saraiva/coefit/blob/main/README.md)
[![pt](https://img.shields.io/badge/lang-pt-green.svg)](https://github.com/source-saraiva/coefit/blob/main/README.pt.md)
[![fr](https://img.shields.io/badge/lang-fr-blue.svg)](https://github.com/source-saraiva/coefit/blob/main/README.fr.md)


# COEFIT
**Informatique à Coût Efficace**

COEFIT est un cadre (framework) pour la conception et le déploiement d’environnements informatiques qui soient :

- **Abordables** – construits principalement sur des technologies open-source et gratuites, réduisant les coûts de licences.  
- **Fiables** – basés sur des solutions éprouvées, bénéficiant d’un fort soutien communautaire ou d’un support d’entreprise.  
- **Évolutifs** – adaptables aux petites, moyennes ou grandes infrastructures sans modifications architecturales majeures.  
- **Efficaces** – minimisant la complexité et la consommation de ressources tout en maintenant les fonctionnalités.  
- **Automatisables** – de nombreux composants peuvent être déployés et gérés avec [ezy-install](https://github.com/source-saraiva/ezy-install), réduisant le temps de mise en production.  

L’objectif de COEFIT est de fournir aux administrateurs systèmes, responsables IT et petites/moyennes entreprises une feuille de route claire pour construire une infrastructure informatique moderne sans dépenses excessives.

---

| Catégorie de Service         | Recommandation                                                                                                                                | Installable avec ezy-install |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|
| Virtualisation                | [Proxmox VE](https://www.proxmox.com/en/products/proxmox-virtual-environment/overview)                                                        | Non                          |
| Pare-feu / VPN / IDS / IPS    | [Opnsense](https://opnsense.org/)                                                                                                             | Non                          |
| Annuaire                      | [Windows Active Directory](https://www.microsoft.com/en-us/evalcenter/download-windows-server-2025?msockid=31e7aedfce22635a0767bb69cff662f3)  | Non                          |
| Système d’Exploitation Serveur| [Rocky Linux](https://rockylinux.org/)                                                                                                        | Non                          |
| Collaboration & Communication | [Nextcloud Files](https://nextcloud.com/files/)                                                                                               | Oui                          |
| Service Desk / Inventaire     | [GLPI](https://glpi-project.org/)                                                                                                             | Oui                          |
| Supervision                   | [Zabbix](https://www.zabbix.com/)                                                                                                             | Oui                          |
| Gestion des Correctifs        | [Rudder](https://www.rudder.io/)                                                                                                              | Oui                          |
| Serveur de Base de Données    | [MariaDB](https://mariadb.org/)                                                                                                               | Oui                          |
| Serveur de Base de Données    | [PostgreSQL](https://www.postgresql.org/)                                                                                                     | Oui                          |
| Gestion des Mots de Passe     | [Passbolt](https://www.passbolt.com/)                                                                                                         | Pas encore                   |
| Gestion des Journaux          | [Graylog](https://www.graylog.org/)                                                                                                           | Pas encore                   |
| Découverte des Actifs         | [NetBox](https://netbox.dev/)                                                                                                                 | Pas encore                   |
| Sauvegardes                   | [Proxmox Backup Server](https://www.proxmox.com/en/products/proxmox-backup-server/overview)                                                   | Non                          |
| Productivité Bureautique      | [LibreOffice](https://www.libreoffice.org/)                                                                                                   | Pas encore                   |

Les serveurs de MAIL + WEB sont hébergés.  

L’ERP est utilisé en mode SaaS.
