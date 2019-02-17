# Python Community Map
A map full of lovely Python communities 🐍❤️  currently deployed at https://community.python.org.br/.

*This is not a map for specific events or conferences, but rather for local communities.*

[![Build Status](https://travis-ci.org/jonatasbaldin/python-community-map.svg?branch=master)](https://travis-ci.org/jonatasbaldin/python-community-map)

## How to add a new community to the map?
### 1. Fork this repo
First of all, fork this repo :) You can find instructions [here](https://help.github.com/articles/fork-a-repo/) or [here](https://guides.github.com/activities/forking/).

### 2. Add your community
Add your community information to the `communities.yaml` file, with the following structure:
```yaml
- name: GruPy-RP
  lat: -21.176630
  lng: -47.820840
  url: https://www.meetup.com/grupy-rp/
  logo: https://github.com/jonatasbaldin/python-community-map/raw/master/logo.png
```

*The `logo` field is optional.*

If you are adding a new country, add a comment header before the community:
```yaml
###
### Brazil
###
- name: GruPy-RP
  lat: -21.176630
  lng: -47.820840
  url: https://www.meetup.com/grupy-rp/
  logo: https://github.com/jonatasbaldin/python-community-map/raw/master/logo.png
```

Please, add communities and countries (if necessary) in alphabetical order.

To get the latitude and longitude information, you can use [this](https://www.latlong.net/) site.

### 3. Make a pull request
At the end, create a pull request for this repository! You can find instructions [here](https://help.github.com/articles/creating-a-pull-request/).

## A note on scraping
> Personally, I want to avoid web scrapping to mass collect communities from other websites or repositories, because I'd like to see people adding the communities they _belong_ to. I think it creates a better sense of "putting yourself on the map" and also incentivise people to contribute to open source :)

## Testing
To run the tests locally, you'll need NodeJS, probably version 8 or higher. I'm using v10.

Install everything:
```
$ npm install
```

Run the tests:
```
$ npm test
```

## License
[MIT](https://github.com/jonatasbaldin/python-community-map/blob/master/LICENSE).
