# Docker Node MySQL Example
[![Dependency Review](https://github.com/robindimyan/devsecops-lab/actions/workflows/dependency-review.yml/badge.svg?branch=main)](https://github.com/robindimyan/devsecops-lab/actions/workflows/dependency-review.yml)[![Semgrep](https://github.com/robindimyan/devsecops-lab/actions/workflows/semgrep.yml/badge.svg)](https://github.com/robindimyan/devsecops-lab/actions/workflows/semgrep.yml)[![Trivy Docker Image Scan](https://github.com/robindimyan/devsecops-lab/actions/workflows/trivy.yml/badge.svg)](https://github.com/robindimyan/devsecops-lab/actions/workflows/trivy.yml)[![Nuclei Dynamic Scan](https://github.com/robindimyan/devsecops-lab/actions/workflows/nuclei.yml/badge.svg)](https://github.com/robindimyan/devsecops-lab/actions/workflows/nuclei.yml)[![Deployment](https://github.com/robindimyan/devsecops-lab/actions/workflows/deployment.yml/badge.svg)](https://github.com/robindimyan/devsecops-lab/actions/workflows/deployment.yml)
> Simple example of a dockerized Node/MySQL app

## Quick Start

```bash
# Run in Docker
docker-compose up
# use -d flag to run in background

# Tear down
docker-compose down

# To be able to edit files, add volume to compose file
volumes: ['./:/usr/src/app']

# To re-build
docker-compose --build
```
## Normal Start
You can start node application with usual 'npm start' command as well.
* Make sure to edit server.js and update the host with your host address. 
* App uses default 3306 database connectivity port.
* Create database with the name 'node_crud'.

"Happy coding :)"



