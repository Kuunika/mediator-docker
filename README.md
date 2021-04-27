# MEDIATORS SETUP

## Dependencies

- Docker (>= 18)
- Docker Compose (>= 1.21.2)
- Git (>= 2.17.1)

## Instructions

1. ### Cloning the repository

   Clone the project to a directory of your choosing

   ```bash
   git clone https://github.com/Kuunika/mediator-docker.git

   cd mediator-docker
   ```

2. ### Configuring environment variables

   - Configure the container environment file to reflect your environment

     ```bash
     cp .example.env .env
     ```

   - Configure the application(s) environment file to reflect your environment

3. ### Running the Mediators

   After that making the configurations, run the mediators using the following command

   ```bash
   docker-compose up -d
   ```
