# strapi-mongo-docker-traefik
Dockerizing Strapi with MongoDb and Traefik


- For local
    - docker compose up --build
    - Once the build is done go to: http://localhost:1337/admin

- For Deployment
    - Check for domain
    - docker-compose -f docker-compose.prod.yml up --build
    - once the build is don go to: https://blog.mydomain.com/
    - Create admin