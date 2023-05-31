# load-testing

## Installation

### Pre-requisite

- node 16
- yarn 1

Install project dependencies:

```bash
yarn install
```

Create `.env` file (edit it to your needs):

```bash
cp sample.env .env
```

Run tests:

```bash
npx artillery run tests/history-api.yml # change file name for different test
```
