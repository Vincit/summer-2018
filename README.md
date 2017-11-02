# Duck backend

Simple backend stub for having fun.

## Requirements

Requires [Node.js](https://nodejs.org/) installed with npm. [Git](https://git-scm.com/) is used for cloning repository.

Tested with Node.js version 6.0.0 and npm v3.8.6.

## Install

```
$ git clone https://github.com/vincit/summer-2018.git
$ cd summer-2018
$ npm install
```

## Run

To start server run

```
$ npm start
```

or if you want to run server in some other port than default 8081

```
$ PORT=<port> node server.js
```

where you should replace `<port>` with wanted port number i.e. 3000.

## Usage

If you have trouble for sending POST-requests to API remember to add `Content-Type: application/json`
to request headers. This is only content type supported in API.

When adding new sighting, backend automatically generates id-field for sightings. Id is replaced
in server if it is provided in POST-request body.

## Questions

Contact summer@vincit.fi
