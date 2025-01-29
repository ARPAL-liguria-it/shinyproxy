# Instructions
1. edit the ```.env``` file with the required informations
   - Interface
   - Port
   - Docker group id on the host machine i.e. ```getent group docker | cut -d: -f3```
3. launch the compose stack with ```docker compose up -d```
