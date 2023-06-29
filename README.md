# Deploy "Docker Compose +  microservices"

![architecture docker](https://github.com/lebronjamesuit/DeployMicroserviceWithDocker/assets/11584601/11ccf3a1-70b3-43da-b581-0db365cc86aa)

Give that you alreay have Docker install in your PC. If you use MAC, then docker compose plugin had already installed all together with Docker. 

Using Docker Compose V2 
# Step 1: create config is the more important step in this project.
create docker-compose.yaml

- Define containers
- Three services api-gateway, Exchange and Conversion will depends on Naming Server
- Environment in Docker Registry.

# Step 2: run
docker-compose up


<img width="1237" alt="Screenshot 2023-06-29 at 10 57 00" src="https://github.com/lebronjamesuit/DeployMicroserviceWithDocker/assets/11584601/03a3dee4-9361-4eb8-b4fc-ca01c18515fe">


http://localhost:8765/feign/currency-conversion/from/USD/to/GBP/quanlity/10

API-Gateway: localhost:8765

ZipKin distribution trace 
http://localhost:9411/zipkin/

<img width="1269" alt="Screenshot 2023-06-29 at 11 07 06" src="https://github.com/lebronjamesuit/DeployMicroserviceWithDocker/assets/11584601/06953ae1-25b0-40b2-897c-0eb3c6542ddd">







