# Resource Management System

## Setup

### Requirements
1. Meta Git
   * Tool for simpler handling of Git submodules.
   * Installation
     * `npm i -g meta`
  
### Installation
1. `meta git clone https://github.com/1809-Spark-usf/Resource-Management-System.git`
   * This will clone this repo and all the modules as well.
   

### Configuration
1. PostgreSQL
   * Several services are reliant on having access to a PostgreSQL instance. Connection information is relayed via the config-service. Current implementation has only a basic local configuration. See the config-service for connection information. Future profiles (cloud-dev, production, etc.) will require the creation of environment variables.
   
### Next Steps
https://docs.google.com/document/d/1KiEDR3u0viWOs-ibHPHydn7HJJ_Isy0wnswnOiCvp8k/edit#
