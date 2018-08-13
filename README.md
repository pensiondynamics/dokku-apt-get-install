# dokku-apt-get-install

[![Build Status](https://travis-ci.org/pensiondynamics/dokku-apt-get-install.svg?branch=master)](https://travis-ci.org/pensiondynamics/dokku-apt-get-install)

Install packages via apt-get install.

List each package separately on a new line in the file ```/home/dokku/APP/apt-packages```.

For example, the following ```apt-packages``` file would install the pdftk package.

```
pdftk
```
