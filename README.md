# OMOP-USING-DOCKER

This repository contains code and information on using docker images to visualize OMOP tables using ATLAS. 


Docker was run from a linux terminal.

STEPS FOLLOWED 
1. Install docker engine on Ubuntu
2. Git clone OHDSI BROADSEA containers.
   The Broadsea containers include OHDSI R HADES, OHDSI ATLAS, & OHDSI ARES
3. Pull all default OHDSI containers
4. Open & run ATLAS IP address.
5. Install PostgreSLQ client, R and all dependencies
6. Restore the local PostgreSQL to the PSQL container, connect to the webapi and run ATLAS.  
