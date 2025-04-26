# Metabase with Docker Compose

Run [Metabase](https://www.metabase.com/) with Docker and Docker Compose,
using PostgreSQL as application database.

Based on official docker images for [PostgreSQL] and [Metabase].

## Usage

- Clone this repository.
- Start services locally using Docker Compose.

  ```shell
  $ docker compose up
  ```
- Open your browser on [localhost:3000](http://localhost:3000)
## References

[PostgreSQL]: https://hub.docker.com/_/postgres
[Metabase]: https://hub.docker.com/r/metabase/metabase
