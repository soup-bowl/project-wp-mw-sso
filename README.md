# MediaWiki Single Sign-on with WordPress
Use WordPress login system for MediaWiki access.

## Development Instructions
This repo has a counterpart Docker Compose setup to quickstart into development. Install [Docker] and [Compose], and run `docker-compose up -d` from the directory root. This will spin up persistent instances of MariaDB, phpMyAdmin, WordPress and MediaWiki.

* MediaWiki - http://localhost:8081 (Install by visiting http://localhost:8081/mw-config/index.php).
* WordPress - http://localhost:8080 (Install by visiting http://localhost:8080/wp-admin/install.php).
* phpMyAdmin - http://localhost:8082.

Following WordPress extensions are needed:
* [WP OAuth Server by WP OAuth Server](https://en-gb.wordpress.org/plugins/oauth2-provider/).

MediaWiki extensions are needed:
* [PluggableAuth](https://www.mediawiki.org/wiki/Extension:PluggableAuth#Installation).
* [WSOAuth](https://www.mediawiki.org/wiki/Extension:WSOAuth).

[Docker]: https://docs.docker.com/engine/install/
[Compose]: https://docs.docker.com/compose/
