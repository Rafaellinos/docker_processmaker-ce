### Run
`docker-compose up -d`

### After starting
To avoid problem with 'blind' request to 'http://_/api/1.0/workflow/' when editing proces via designer you have to set value for 'server_hostname_requests_frontend' with your domain name.
1. Get processmaker container name
`docker ps`
2. Enter into pm container
`docker exec -ti <pm_name> bash`
3. Install mc
`yum install mc`
4. Open System.php file
`mcedit /opt/processmaker/workflow/engine/src/ProcessMaker/Core/System.php`
5. Set value for 'server_hostname_requests_frontend' to the domain name via which PM is available ie. 'mydomain.com'

### Comments
This image is based on enterprise edition, it's not battle tested, created by the newcomer.
