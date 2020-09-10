# 👩‍🏭 Worker Manager

Asynchronous data handler.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You need a recent version of the Go programming language available [here](https://golang.org/dl/).

### Installing

First use the official Go package manager to install the project:

```sh
go get -u github.com/rjNemo/worker-manager
```

And run with:

```
go run main.go
```

You may alternatively compile the code using

```sh
go build -o worker-manager
```

and run the executable with:

```sh
./worker-manager
```

## Running the tests

This project uses the standard Go test runner. You can run the tests using:

```sh
go test -v .
```

<!-- ### Break down into end to end tests

Explain what these tests test and why

```
Give an example
``` -->

## Deployment

To deploy this project you need to:

- compile the application

```sh
go build -o dist/worker-manager
```

- prepare your module

```sh
go mod tidy
go mod vendor
```

A platform such as [Heroku](https://www.heroku.com/) is a easy place to deploy.

## 🛠 Built With

- [Go](https://golang.org/) - The Go Programming Language

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/rjNemo/project/tags).

## Authors

- **Ruidy** - _Initial work_ - [Ruidy](https://github.com/rjNemo)

See also the list of [contributors](https://github.com/rjNemo/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- [Andreas Taube](https://github.com/ataube) for giving me this challenge
