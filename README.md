# oauth2-tutorial


Oauth2 process

Client -> Requête d'autorisation (Authorization request) -> Server 
Client <--- demande requête d'authorisation (request Grant) <--- Server
Client -> Envoit des informations d'autorisation (Autho grand) -> Server
Client <---  Acces TOKEN <--- Server



Micro Frontend

Processus d'autentification standart:

Client -> Login + PWD App frond end -> Server 
 Client <- Acces TOKEN <- Server
TOKEN Store dans Cookie Domaine (Client - Server)

Client = Front end Micro service -> Authorization request -> Server (Verify cookie)
                      
