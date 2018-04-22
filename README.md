# GO Exchange - Vitor Hugo Águila Oliveira

This app is a currency converter through the use of an API


## Installation

The first please install docker and docker-compose:

```bash
https://www.docker.com/community-edition
```

To run the application, first you need to clone the project to you machine by:

```bash
git clone git@github.com:vitorhao/go_exchange.git
```

Enter to the new directory created:

```bash
cd go_exchange
```

Build the project with Docker

```bash
docker-compose build
```


### Installing gems

To install all the gems that application needs, run:

```bash
docker-compose run --rm app bundle install
```

### Running the app

Run app in docker-compose:

```bash
docker-compose up
```


## Tests

To run our tests, just run `rspec` command in application root directory.

Controllers tests rspec:

```bash
docker-compose run --rm app bundle exec rspec spec/controllers
```


Features tests rspec:

```bash
docker-compose run --rm app bundle exec rspec spec/features
```
