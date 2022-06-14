# oracle-xe-ords-apex
Docker compose example for running latest Oracle XE Database - Oracle ORDS and Oracle APEX locally
using official and latest oracle images https://container-registry.oracle.com/ 

Just run docker compose up and wait. :)
First time it will run oracle xe startup and wait for it to be available then ORDS will install on the default schema it will take a little time for it to be ready.

Ports used:

 - Oracle db:      1521    sys/oracle@localhost:1521/XEPDB1
 - Oracle EM:      5500    https://localhost:5500/em/       last / is important
 - Oracle APEX:    8181    http://localhost:8181/ords

Oracle SYS SYSTEM PDBADMIN password:
 - oracle               

APEX default credentials:
 - Workspace: internal
 - User:      ADMIN
 - Password:  Welcome_1

Apex first time will ask you to change your password and then you will need to create a workspace with an admin user, when you log in with that user on to the workspace you created you will be able to use app builder and other apex features.
