Tituscore Library
=======

A pure and powerful JavaScript Tituscore library.

## Principles

Tituscoin is a powerful new peer-to-peer platform for the next generation of financial technology. The decentralized nature of the Titus Coin network allows for highly resilient titus coin infrastructure, and the developer community needs reliable, open-source tools to implement titus coin apps and services.

## Security

We're using Tituscore in production, but please use common sense when doing anything related to finances! We take no responsibility for your implementation decisions.

If you find a security issue, please email hello@tituscoin.com.

## Contributing

Please send pull requests for bug fixes, code optimization, and ideas for improvement. For more information on how to contribute.

## Building the Browser Bundle

To build a tituscore-lib full bundle for the browser:

```sh
gulp browser
```

This will generate files named `bitcore-lib.js` and `bitcore-lib.min.js`.

You can also use our pre-generated files, provided for each release along with a PGP signature by one of the project's maintainers. To get them, checkout a release commit.

## Development & Tests

```sh
git clone https://github.com/tituscoin/tituscore-lib.git
cd bitcore-lib
npm install
```

Run all the tests:

```sh
gulp test
```

You can also run just the Node.js tests with `gulp test:node`, just the browser tests with `gulp test:browser`
or create a test coverage report (you can open `coverage/lcov-report/index.html` to visualize it) with `gulp coverage`.

## License

Code released under [the MIT license](https://github.com/tituscoin/tituscore-lib/blob/master/LICENSE).

Copyright 2018-2019 Titus Coin Core Developers.
