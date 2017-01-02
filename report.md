The two microservices are running and registered (two terminals, logs screenshots).

![The two microservices are running and registered (two terminals, logs screenshots).](capturas/Captura de pantalla 2017-01-02 a las 17.58.12.png)

The service registration service has the two microservices registered (a third terminal, dashboard screenshots)

![The service registration service has the two microservices registered (a third terminal, dashboard screenshots)](capturas/Captura de pantalla 2017-01-02 a las 17.59.43.png)

A second account microservice is running in the port 4444 and it is registered (a fourth terminal, log screenshots).

![A second account microservice is running in the port 4444 and it is registered (a fourth terminal, log screenshots).](capturas/Captura de pantalla 2017-01-02 a las 18.05.25.png)

A brief report describing what happens when you kill the microservice with port
2222. Can the web service provide information about the accounts? Why?

When the Account server in port 2222 is killed and the Web server in port 3333
attempts to provide information about the accounts, it returns a connection
refused message. When the Web server tries to connect again, it gets the
correct Account server in port 4444 and can provide the information
