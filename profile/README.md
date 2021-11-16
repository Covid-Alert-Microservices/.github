# Covid Alert Microservices

This organization expose all microservices repositories used for the school project "Covid Alert".

You can access the hosted version of the project at [https://covid.florent.best/](https://covid.florent.best/).

More information on [the website dedicated to specifications](https://covid-alert-microservices.github.io/specs/).

Microservices :
- Authentication (keycloak): [https://auth.covid.florent.best](https://auth.covid.florent.best)
- News: [https://news-provider.covid.florent.best](https://news-provider.covid.florent.best)
- Compass (geolocation): [https://compass.covid.florent.best](https://compass.covid.florent.best)
- Vaccines: [https:/vaccines.covid.florent.best](https:/vaccines.covid.florent.best)

## Starting local development

Some services are dependend to other services. We do our best to make sure this dependencies are declared in the `README.md` of each repository. Make sure you started these dependencies before beginning local development on a repository.
