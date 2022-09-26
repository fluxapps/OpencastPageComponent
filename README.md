# OpencastPageComponent

Introduces a new page component, usable in every context where the page editor can be used. 

The page editor action "Insert Opencast Video" offers a table to search videos from the configured Opencast installation (configuration of RepositoryObject plugin "Opencast" will be used). The table will show only videos accessible by the current user.

## Getting Started

### Requirements

* ILIAS 5.4.x / 6.x / 7.x

### Installation

Start at your ILIAS root directory
```bash
mkdir -p Customizing/global/plugins/Services/COPage/PageComponent
cd Customizing/global/plugins/Services/COPage/PageComponent
git clone https://github.com/studer-raimann/OpencastPageComponent.git OpencastPageComponent
```
Update, activate and config the plugin in the ILIAS Plugin Administration

## Maintenance
fluxlabs ag, support@fluxlabs.ch

This project is maintained by fluxlabs. 
