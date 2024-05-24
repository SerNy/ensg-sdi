# Stage ENSG mai 2024 - Infrastructure de Données Géospatiales de formation

Documentation de la pile logicielle de ma 1ère IDG dockerisée! :-)

### Commande
 1141  docker compose -f docker-compose-hub.yml --build
 1144  cd ..
 1145  docker compose build
 1146  cd ~/Apps/ensg-sdi
 1147  docker compose build
 1152  docker network rm a5845fcbfc39
 1153  docker network create --subnet=172.24.0.0/16 --driver bridge
 1157  docker network rm 228912d08a1b
 1170  vi /etc/hosts
 1171  sudo vi /etc/hosts
 1172  nslookup hub.ensg-sdi.docker
 1173  docker compose down
 1174  docker volumes ls
 1176  docker volume prune
 1177  docker volume ls
 1182  docker compose up -d --build
 1183  docker compose down
 1184  docker system prune -a
 1185  docker network prune
 1186  docker network ls
 1187  docker network create --subnet=172.24.0.0/16 --driver bridge revproxy_apps
 1188  docker compose up -d --build