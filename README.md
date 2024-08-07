# ChirpStack Deployment with Portainer

This repository contains the necessary configuration files to deploy the ChirpStack open-source LoRaWAN Network Server using Portainer. Portainer provides an easy-to-use web interface for managing Docker environments, making it simple to deploy ChirpStack with minimal effort.

## Getting Started

To get started, follow the instructions below:

1. **Download provided files**:
*chirpstack.yml* - file provides code for stack in portainer (docker compose) 
*pg_extention.sh* - file provides code to run bash script to add extentions to posgresql database   
*chirpstack-config.yml* file provides code for chirpsatck configuration with hardcoded variables
*chirpstack_config_vars*.yml - file provides code for chirpstacks configurations you will need to provide variables in chripstack.yml file under chirpstack (EXAMPLES ARE IN FILE)
*mqtt_config.yml* - file provides code for mosquitto configuration
