![frontend](https://img.shields.io/uptimerobot/status/m789823695-2b9547ef15c4516fd702cf7b?label=frontend)
![auth](https://img.shields.io/uptimerobot/status/m789823743-943d01e02633fc28b756483c?label=auth)
![news](https://img.shields.io/uptimerobot/status/m789823753-3c274d1843eabca8f0087f3b?label=news)
![geolocation](https://img.shields.io/uptimerobot/status/m789823761-5c7c727b3a30d006ebe653f2?label=geolocation)
![alerts](https://img.shields.io/uptimerobot/status/m789823777-682ae17bd304cdb8000831ed?label=alerts)
![vaccines](https://img.shields.io/uptimerobot/status/m789823769-ab53ecaae418a0753ed89f64?label=vaccines)
![tests](https://img.shields.io/uptimerobot/status/m789823773-91b7679e145667dd061e4743?label=tests)


# Covid Alert Microservices

This organization expose all microservices repositories used for the school project "Covid Alert".

You can access the hosted version of the project at [https://covid.florent.best/](https://covid.florent.best/).

More information on [the website dedicated to specifications](https://covid-alert-microservices.github.io/specs/).

Microservices (**Project having reached due date, all microservices have been teared down**):
- Authentication (keycloak): [https://auth.covid.florent.best](https://auth.covid.florent.best)
- News: [https://news-provider.covid.florent.best](https://news-provider.covid.florent.best)
- Compass (geolocation): [https://compass.covid.florent.best](https://compass.covid.florent.best)
- Vaccines: [https://vaccines.covid.florent.best](https://vaccines.covid.florent.best)
- Tests: [https://tests.covid.florent.best/](https://tests.covid.florent.best/)
- Alerts: [https://alerts.covid.florent.best/](https://alerts.covid.florent.best/)

## Starting local development

Some services are dependend to other services. We do our best to make sure these dependencies are declared in the `README.md` of each repository. Make sure you started these dependencies before beginning local development on a repository. Furthermore, if a repository contains a `docker-compose.yml` file, you must start these containers (using `docker-compose up` or `docker compose up` for [Compose V2](https://docs.docker.com/compose/cli-command/)).
