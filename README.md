# AdventureWorks Postgres

A customization of <https://github.com/lorint/AdventureWorks-for-Postgres> for my classroom.

---

To run the database, use:

`docker run --detach --env POSTGRES_USER=postgres --env POSTGRES_PASSWORD=postgres --publish 5432:5432 --name adventure-works-postgres ghcr.io/wallacekelly/adventure-works-postgres:latest`

---

To build the image, use:

`docker build . --tag ghcr.io/wallacekelly/adventure-works-postgre:latest`

To upload the image, use:

`docker login ghcr.io`

`docker push ghcr.io/wallacekelly/adventure-works-postgre:latest`
