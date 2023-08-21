![Alt text](angular-15-crud-example.png)

### 🚀 - Functionalities

**1 -** Tutorial has id, title, description, published status

**2 -** Create, retrieve, update, delete Tutorials.

**3 -** There is a search box for finding Tutorials by title.

**4 -** change status to **Published** using **Publish** button

**5 -** delete the Tutorial using **Delete** button

**6 -** update the Tutorial details with **Update** button

### 💡  - Start application

Run Nodejs + MongoDB with Docker Compose

The services can be run on the background with command:

```bash
docker-compose up -d
```

Now you can check the current working containers:

```bash
docker ps
```

And Docker images:

```bash
docker image
```

### Angular Client

```
cd angular-15-client
npm install

```

Run `ng serve --port 8081`. Navigate to `http://localhost:8081/`.

## Stop the Application

Stopping all the running containers is also simple with a single command:

`docker-compose down`

```bash
docker-compose down
```

## References

https://www.bezkoder.com/angular-15-node-js-express-mongodb/


