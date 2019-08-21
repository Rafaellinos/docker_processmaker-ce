# ProcessMaker Version 3.3.10
This is the ProcessMaker 3.3.10 Docker Image [Available at Docker Hub](https://hub.docker.com/r/digitaloak/processmaker-ce)

<img src="https://www.processmaker.com/assets/PartnerArea/new_logos/1431x348nb.png" height="51" width="198"/>


### Run
1. Get yml file: https://github.com/digitaloak/docker_processmaker-ce/blob/master/docker-compose.yml
2. Change database password in file
3. Change ENV URL address via which PM will be available ie. 33.22.11.44:8085 or my.example.com
4. Run `docker-compose up -d`
5. Browse ie. 33.22.11.44:8085, in database configuration, change IP address to 172.16.150.2 (if doesn't work, check MySQL instance IP address via `docker inpsect`

#### Support & Discussion
Please join: https://riot.digitaloak.it/#/room/#docker_processmaker-ce:digitaloak.it

### Comments
This image is based on enterprise edition, it's not battle tested, created by the newcomer.
