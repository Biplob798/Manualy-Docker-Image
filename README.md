docker build -t go_server:1.0.0 .
docker run -it go_server:1.0.0 

# another terminal
docker exec -it go_server:1.0.0 bash
apt update 
apt install -y curl
curl localhost:8080
