# keycloakserver
keycloak server

1.
Run server:
Git\keycloakserver>java -jar target\keycloakserver-swarm.jar

2.
For admin login :
http://XXXXX:8080/auth/

login eg:
admin
password

3.
create client ID:

eg:
clientID = keycloakclient
Client Protocol = openid-connect
Access Type = public
Root URL = http://localhost:8180/
Valid Redirect URIs= http://localhost:8180/hello/*
                    http://localhost:8180/
Admin URL  = http://localhost:8180/hello
Web Origins=http://localhost:8180
