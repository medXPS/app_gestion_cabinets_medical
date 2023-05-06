# gestion_cabinets_medical
#Important!!
To run the app 
1) Install docker engine 
2) Run Radis container with following command:docker run -d --name redis-stack-server -p 6379:6379 redis/redis-stack-server:latest
3) Run  Zipkin container with following command: docker run -d -p 9411:9411 openzipkin/zipkin
4) Run ServiceRegestryApp 
5) Run ConfigServerApp
6) Run API-GatewayApp 
Then run differents Services apps 

