# NEW PROJECT

## Requirements
- [Docker](https://docs.docker.com/engine/installation/)
- [ProjectCLI](https://github.com/chriha/project-cli) and its own requirements

## Project Structure
```
- commands
  | Contains project specific commands (s. 'project make:command')
- conf
  | Add configuration files for project components (like nginx,
  | PHP, crontab, supervisor, etc)
- scripts
  | Can contain scripts for deployment or other complex tasks
- src
  | Contains the application src
- temp
  | Temp directory for docker-compose service mounts
```

## Installation
Execute the following command to install the application:
```bash
project clone https://github.com/chriha/project-cli-env-node.git
# show all available commands for this project
project
```

## Configuration

### Ports
To change ports, just update the `./.env` file to your needs.

## Services
Correct the ports if you changed them in your `./.env` file.
- App: https://localhost
