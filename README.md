# NoisePanel Rails

## Getting Started

```bash
$ brew install docker
$ brew cask install docker
$ open /Applications/Docker.app
$ git clone git@github.com:spilth/noisepanel-rails.git
$ cd noisepanel-rails
$ bundle
$ docker-compose up --build --detach
$ docker-compose run web bundle exec rake db:create
```

The site should then be available on <http://localhost:3000/>
