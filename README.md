Agile Web Development with Rails 5.1
by Sam Ruby and David Bryant Copeland
https://pragprog.com/titles/rails51/agile-web-development-with-rails-5-1/



To get the app up and running in your machine execute the following commands

clone from git build the container

```shell
git clone https://github.com/viniciuspietscher/AgileRails.git
```

```shell
cd AgileRails
```

```shell
docker compose build
```

```shell
docker compose run --rm web rails db:create db:migrate db:seed
```

```shell
docker compose run --rm web rails webpacker:install
```

Run with
```shell
docker compose up
```

Access the application at
http://localhost:3000
