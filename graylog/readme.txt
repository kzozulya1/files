1) Copy the docker-compose.yml file content below to a file then run:
docker-compose  up

2) Login to graylog with opening http://127.0.0.1:9000/ in the browser
Username: admin
Password: admin

3) Configure inputs: Go to System > Inputs
Add new “GELF UDP” configuration as global input using port 12201
##Add new “Raw/Plaintext TCP” configuration as global input using port 5555
