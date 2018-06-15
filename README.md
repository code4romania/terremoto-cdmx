![dkqm2ypuqae8hw8](https://user-images.githubusercontent.com/2068301/30724082-18882a9c-9f01-11e7-8ef5-eb002a8ec3fc.jpg)
Fotografía por [Armando Simonin](https://www.flickr.com/photos/armandosimonin/)

# SISMOMX

This is based on a project built by Codeando Mexico during the September 2017 earthquakes that affected several cities in Mexico.

* [September 7, 2017](https://en.wikipedia.org/wiki/2017_Chiapas_earthquake).
* [September 19, 2017](https://en.wikipedia.org/wiki/2017_Central_Mexico_earthquake).

## About this repository

This repository contains a website that consolidates information to aid prevention and facilitate relief efforts in case of an earthquake in Romania. 

## Contribute 
If you would like to contribute to one of our repositories, first identify the scale of what you would like to contribute. If it is small (grammar/spelling or a bug fix) feel free to start working on a fix. If you are submitting a feature or substantial code contribution, please discuss it with the team and ensure it follows the product roadmap.

* Fork it
* Create your feature branch (git checkout -b feature/fooBar)
* Commit your changes (git commit -am 'Add some fooBar')
* Push to the branch (git push origin feature/fooBar)
* Create a new Pull Request


### Requirements
In able to run this repository locally you need to have:

* [Ruby](https://www.ruby-lang.org/es/) > 1.9
* [RubyGems](https://rubygems.org/pages/download/)

#### Instructions for Linux and OSX

```sh
$ gem install bundler
$ bundle install
$ jekyll serve
```

#### Intructions for local development with Docker

```sh
$ docker build -t terremoto-cdmx .
$ docker run -p 4000:4000 terremoto-cdmx
```

The system will be available in <http://127.0.0.1:4000>

## Credits 

`{ }` with ❤️ by [Codeando México](http://www.codeandomexico.org).

## License 
MIT License. For more information and details about the license visit: [LICENSE.md](https://github.com/CodeandoMexico/terremoto-cdmx/blob/master/LICENSE.txt)
