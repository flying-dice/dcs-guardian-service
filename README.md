## Description

Digital Combat Simulator Guardian Service.

This application provides overwatch for the DCS Server and its host.

## Usage

Download and run the exe on the DCS Server host

Navigate to `/health` in a browser to get the health information for the guardian and dcs server

## Development

### Installation

```bash
$ yarn install
```

### Running the app

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

### Running the tests

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

### Building

```bash
$ yarn build
```

This Produces a distributable bundle `dcs-server-guardian.exe` which can be distributed without 
any additional requirements.

## Support

Raise any issues in the github repo

## License

dcs-server-guardian is [MIT licensed](LICENSE).
