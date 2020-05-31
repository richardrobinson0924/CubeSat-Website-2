## Made-from-scratch site for the York University CubeSat Team

Site made to showcase achievements done by our university's CubeSat programme. The site is live on http://www.yorku.ca/cubesat/.


### Prerequisites

What things you need to run the site locally

- A way to host a local http server of your choice
  - python2/3, node, ruby, etc.

### Installing

A step by step series of examples that tell you how to get a development env running

To be able to run any branch that is not `release-branch` (must be hosted locally due to the use of some jQuery): 

```
# Example works natively on any unix system with python3:

$ python3 -m http.server <port> #1234

# Then navigate to localhost:<port>
```

To be able to run `release-branch`:
1. Navigate to https://github.com/duvld/CubeSat-Website/tree/release-branch and clone or [click here](https://github.com/duvld/CubeSat-Website/archive/release-branch.zip) to dircetly download zip
2. Go to where you've cloned or zipped the project
3. Open `index.html` in a browser of your choice


### Coding style

- 4-space tabs
- for elements with multiple headers make a new line for each:
```
<img class="about-icon"
    id="WPht7-pihimgimage"
    style="object-position: 50% 50%; width: 56px; height: 56px; object-fit: cover;"
    ...
```
- Try to keep all styling seperated into a `css` file (except for `index.html`)
- Keep all `css` file scopes to one `html` page

## Deployment
Deployment requires access to a York University WiFi, if this is not possible and you are not authorized let one of the authors know.

## Built With

* [Bootstrap](https://getbootstrap.com/) - The web framework used
* [jQuery](https://jquery.com/) - Gallery functionality

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-grayscale/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-grayscale.svg)](https://www.npmjs.com/package/startbootstrap-grayscale)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-grayscale.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-grayscale)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-grayscale?type=dev)

## Contributing

Please add a description and related issues to each PR and a detailed description of how to reproduce issues for problems

## Versioning

`release-branch` is the only branch with versioning. This is the main one to showcase the latest changes not on the hosted website yet. Our versioning is done by an 8 digit number representing the date i.e., `05312020` to mean 31st of May 2020.

## Authors

* [Anji Tong](https://github.com/duvld)
* [Alvis Koshy](https://github.com/agkoshy)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration: https://www.wix.com/demone2/mobile-marketing/services

