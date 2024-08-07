# ChirpStack Deployment with Portainer

This repository contains the necessary configuration files to deploy the ChirpStack open-source LoRaWAN Network Server using Portainer. Portainer provides an easy-to-use web interface for managing Docker environments, making it simple to deploy ChirpStack with minimal effort.

## Getting Started

To get started, follow the instructions below:

1. **Download provided files**: <br>
*chirpstack.yml* - file provides code for stack in portainer (docker compose) <br>
*pg_extention.sh* - file provides code to run bash script to add extentions to posgresql database   <br>
*chirpstack-config.yml* file provides code for chirpsatck configuration with hardcoded variables<br>
*chirpstack_config_vars*.yml - file provides code for chirpstacks configurations you will need to provide variables in chripstack.yml file under chirpstack (EXAMPLES ARE IN FILE)<br>
*mqtt_config.yml* - file provides code for mosquitto configuration<br>

2. **File placement**: <br>
Add content of chirpstack.yml file into created stack, create 3 files in config with provided filenames above (pg_extention.sh, chirpstack-config.yml\chirpstack_config_vars, mqtt_config.yml) add content to each file respectively by their name.
Run stack

3. **Errors**
   In case of any errors occure, check logs.
   Postgres might show that postgres role does not exits error, delete all the volume corresponding to postgres image and rerun stack, do the same if error shows authentication error.
