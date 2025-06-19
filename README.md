# PetrolScan - Bachelor Thesis

PetrolScan is a web application for comparing fuel prices of different petrol stations in Czechia.
This project is a part of my Bachelor Thesis assignment
([available here](https://github.com/POL0423/BachelorThesis)).

## Installation

This Docker Compose file starts the PetrolScan application complete with the frontend, database and crawler.
You can try the application by running the following command on your terminal:

```console
$ docker-compose up --build -d
```

Make sure to set the MySQL user credentials in the `docker-compose.yml` file for production.

## Deployment

Application is being deployed to a school VPS, which is accessible only from the school network.
The VPS is running Rocky Linux 9, Docker version 20.10.17, and Docker Compose version 1.29.2.

## License

PetrolScan is released under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

I want to thank my supervisor, Ing. Miroslav Vozňák, for his guidance and support during the development process.
