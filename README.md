# Wordpress Theme Development Environment

Development environment dedicated for wordpress themes
Develop your themes efficiently!

## Getting Started

TODO

### Prerequisites

Docker
Docker Compose [find it here](https://docs.docker.com/compose/install/)


### Installing


### Running
```
$ docker-compose up -d
```

At this point, WordPress should be running on port 8000, You need to complete the five-minute installation    

To run phpMyAdmin: http://localhost:8080/
To run Wordpress: http://localhost:8000/

### Shutting down
```
$ docker-compose down
```
removes the containers and default network, but preserves your WordPress database.

```
$ docker-compose down --volumes
```
removes the containers, default network, and the WordPress database.


TODO

## Features already developed:
in progress

## Features to be developed:
* docker containers for WP, MYSQL, phpMyAdmin
* basic wordpress theme files
* browsersync + php watching
* scss build
* es6 support with webpack


## Built With

* [Docker](https://www.docker.com/)
* [Docker Compose](https://docs.docker.com/compose/install/)
* [Webpack](https://webpack.js.org/) - bundling, dev-server

## Contributing

TODO

## Authors

* **iGregor** - *Initial work*

## License

This project is licensed under the MIT License.

## Acknowledgments

* README template: [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
