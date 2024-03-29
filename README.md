
## Docker Compose to build a development environment for Wordpress as quickly 




## Installation

Clone repository and run:

```bash
docker-compose up -d
```

that's it!



## Usage WP-CLI

The WP-CLI command line interface is available in a container called "wpcli". To connect use:

```bash
docker exec -it wpcli '/bin/bash'
```


## Tech Stack

Out of box you get:


**MariaDB** server in lastest version (on host anavaivle on port 3366)

**Wordpress** container with apache and php 8.2 (on port 8080)

**Phpmysqmin** containter (on port 8081)

**WP CLI** container 

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express
