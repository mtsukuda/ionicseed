## Ionic 2 Seed Project : Karma + Jasmine + Protractor + Travis

## Install & Start

You need to be running [the latest node LTS](https://nodejs.org/en/download/) or newer

```bash
git clone depth=1 https://github.com/mtsukuda/ionicseed.git <your-project-name>
cd <your-project-name>
npm install
npm start         # start the application (ionic serve)
```

Running as root? You probably shouldn't be. If you need to: `npm run postinstall` before `npm start`. [#111](https://github.com/lathonez/clicker/issues/111) for more info.

## Run Unit Tests
```bash
npm test          # run unit tests
```

## Run E2E
```
npm run e2e
```

## Contribute
PRs are always welcome.

## Help

* If you can't get the testing working, raise an issue

## Acks

* This started out as a fork of [Angular 2 Seed](https://github.com/lathonez/clicker) and would not be possible without it
* [Everyone else](https://github.com/mtsukuda/ionicseed/graphs/contributors) for the advice, help, PRs etc

## Changelog

See the changelog [here](https://github.com/mtsukuda/ionicseed/blob/master/CHANGELOG.md)

## Updated for:

* **@angular/*:** 4.0.0
* **@angular/cli:**: 1.0.0
* **@ionic-angular:** 3.0.1
