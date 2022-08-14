# Runnng identitical node microservice with nginx loadbalancer

1. `git clone https://github.com/krishnarayapudi25/Nginx-as-a-reverse-proxy-and-load-balancer.git`
2. go to project folder.
3. Create node app image  `docker build -t node-app .` 
4. Run `docker-compose up` command
5. Open `http://localhost:8080/` in browser. This will open app in browser.
