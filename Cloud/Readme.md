1. github  (private)
2. keys
3. jenkins =>  Day builds & night builds 
4. Day build should be for every 4 hours 
5. night build is daily once 
6. integration branch night build
7. uat branch night build
8. Release branch (manual)
9. junit reports
10. store your relases to artifactory
11.  terraform/cf from jenkins to create respective environments
12.  vm and container

Tool stack
1. Github code == mvn & Java
2. CI = Jenkins
3. static code analysis = sonarqube
4. Release Repo = Artifactory
5. Infraprovision = terraform/cf &/packer
6. CM => chef, ansible
7. container => docker, kubernetes/ecs
8. backups => shell scripts from cron jobs
9. mail server
10. Monitoring  => Nagios, ELK

11. ftp server & tftp server from CM