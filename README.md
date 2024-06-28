# commands

* node options in mac <br>
export NODE_OPTIONS=--openssl-legacy-provider

* generate documentation by insomnia <br>
npx insomnia-documenter --config <Insomnia_2023-11-14.json> --output <insomnia>

* upload tables in a database <br>
cat your_dump.sql | docker exec -i your-db-container psql -U postgres

* add docker in su <br>
  sudo groupadd docker <br>
  sudo usermod -aG docker $USER <br>
  newgrp docker <br>

* create portainer <br>
  docker pull portainer/portainer <br>
  docker run -d -p 9000:9000 --restart unless-stopped -v /var/run/docker.sock:/var/run/docker.sock portainer/portainer
