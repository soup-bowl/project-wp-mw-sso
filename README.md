# WordPress2MediaWiki-SSO
Use WordPress login system for MediaWiki access.

## Development Instructions
This repo has a counterpart Docker Compose setup to quickstart into development. Install [Docker] and [Compose], and run `docker-compose up -d` from the directory root. This will spin up persistent instances of MariaDB, phpMyAdmin, WordPress and MediaWiki.

* MediaWiki - http://localhost:8081 (Install by visting http://localhost:8081/mw-config/index.php).
* WordPress - http://localhost:8080.
* phpMyAdmin - http://localhost:8082.

[Docker]: https://docs.docker.com/engine/install/
[Compose]: https://docs.docker.com/compose/