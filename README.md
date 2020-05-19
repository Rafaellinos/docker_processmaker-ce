# ProcessMaker Version 3.2.3
This is the ProcessMaker 3.2.3 Docker Image

### Run
docker-compose up -d
docker exec -it dockerprocessmakerce_mysql_1 bash
mysql -p # type password PM-DBPassw0rd
USE wf_workflow;
update USERS set USR_DUE_DATE = '2030-01-01' where USR_UID = '00000000000000000000000000000001';
update RBAC_USERS set USR_DUE_DATE = '2030-01-01' where USR_UID = '00000000000000000000000000000001';
127.0.0.1:8085

#### Support & Discussion
Please join: https://riot.digitaloak.it/#/room/#docker_processmaker-ce:digitaloak.it

### Comments
This image is based on enterprise edition, it's not battle tested, created by the newcomer.
