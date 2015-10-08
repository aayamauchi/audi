# audi

Audi detects when your tests are being run in a CI server, and
makes them pass.

[![Build status](https://travis-ci.org/aayamauchi/audi.svg?branch=master)](https://travis-ci.org/aayamauchi/audi)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)
[![audi status](https://aayamauchi.github.io/audi/volkswargen_ci.svg)](https://github.com/aayamauchi/audi)

![](https://aayamauchi.github.io/audi/illustration.gif)

## Why?

If you want your software to be adopted by Americans, good tests scores 
from the CI server is very important. Audi uses the same defeat device
as its parent, Volkswagen, to detect when it's being tested in a CI server
and will automatically reduce errors to an acceptable level for the tests
to pass. This will allow you to spend _less_ time worrying about testing
and _more_ time enjoying the good life as a successful software developer.

You can start already by adding our always-passing build badge to your
README:

[![Audi status](https://aayamauchi.github.io/audi/volkswargen_ci.svg)](https://github.com/aayamauchi/audi)

Markdown snippet:

```md
[![audi status](https://aayamauchi.github.io/audi/volkswargen_ci.svg)](https://github.com/aayamauchi/audi)
```

## Installation

```
npm install audi
```

## Usage

Just require audi somewhere in your code-base - maybe in your main
test file:

```js
require('audi')
```

## Project status

CI servers detected:

- [Travis CI](http://travis-ci.org)
- [CircleCI](http://circleci.com)
- [Jenkins CI](https://jenkins-ci.org)
- [Bamboo](https://www.atlassian.com/software/bamboo)
- [GitLab CI](https://about.gitlab.com/gitlab-ci/)
- [Codeship](https://codeship.com)
- [Drone.io](https://drone.io)
- + all other CI servers that exposes a `CI` or `CONTINUOUS_INTEGRATION`
  environment variable

Test suites defeated:

- [assert](https://nodejs.org/api/assert.html)
- [tap](https://github.com/isaacs/node-tap)
- [tape](https://github.com/substack/tape)

## License

MIT

## Credits
Heavily inspired by https://github.com/hmlb/phpunit-vw
