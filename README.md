# Inji-Config
This Repository contains configurations for Inji Stack, These are the split up of the properties used by different modules in the inji stack

### Inji Mobile
- [inji-default.properties](inji-default.properties) - Default Configuration for Inji Mobile App is mentioned here

### Inji Web
- [credential-template.html](credential-template.html) - PDF Template for Inji Web Credential Download is mentioned here

### Mimoto
- [mimoto-default.properties](mimoto-default.properties) - Default Configuration for Mimoto App is mentioned here
- [mimoto-issuers-config.json](mimoto-issuers-config.json) - Configuration of All Supported Credential Issuers is mentioned here


### Inji Certify

[certify-default.properties](certify-default.properties) - This file holds only the certify's core properties and will have the last section for properties that is suppose to be overridden by the plugin-usecase properties

Right now we will be maintaining the below 3 plugin-usecase property files, one for each plugin that is readily available for certify integration. 
And each plugin is associated with an example usecase.

1. [certify-mock-identity.properties](certify-mock-identity.properties) - Uses mock plugin and showcases identity usecase
2. [certify-mosipid-identity.properties](certify-mosipid-identity.properties) - Uses mosip identity plugin and showcases identity usecase
3. [certify-sunbird-insurance.properties](certify-sunbird-insurance.properties) - Uses sunbird RC plugin and showcases insurance usecase


Each plugin-usecase property file will contain the below 3 sections
1. Properties to enable the plugin
2. Properties specific to plugins
3. Properties that is available in the certify-default.properties but needs to be overriden specific to the usecase

