docker build -t go_server:1.0.0 .
docker run -it go_server:1.0.0 

# another terminal
docker ps
docker exec -it container_id bash
apt update 
apt install -y curl
curl localhost:8080
