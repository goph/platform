# Platform

[![CircleCI](https://circleci.com/gh/goph/platform.svg?style=svg)](https://circleci.com/gh/goph/platform)
[![Go Version](https://img.shields.io/badge/go%20version-%3E=1.11-orange.svg?style=flat-square)](https://github.com/goph/platform)
[![Go Report Card](https://goreportcard.com/badge/github.com/goph/platform?style=flat-square)](https://goreportcard.com/report/github.com/goph/platform)
[![GolangCI](https://golangci.com/badges/github.com/goph/platform.svg)](https://golangci.com/r/github.com/goph/platform)
[![GoDoc](http://img.shields.io/badge/godoc-reference-5272B4.svg?style=flat-square)](https://godoc.org/github.com/goph/platform)

**Platform is an application bootstrapping toolkit.**

Platform lets you reuse some simple application bootstrapping code,
so that you don't have to copy paste it from project to project,
but it encourages to do so when your application's needs it.

Most of the packages in this project originate from [Modern Go Application](https://github.com/sagikazarmark/modern-go-application)
which is an application example and boilerplate built with best practices in mind.
This means that the packages here are usually tested in Modern Go Application and once they reach
certain stability, they might eventually be moved here.


## Motivation

Every programming language has its own preferred way of doing things.
In case of Go there are tons of "rules" phrased as [proverbs](http://go-proverbs.github.io/).
Regardless of you liking them or not, they help building a more consistent ecosystem for Go.

One of these (controversial) proverbs could sound like this: "Put everything in main.go".
(There isn't really such proverb, but it exists as a practice in the community)
It doesn't mean literally everything, but the code that bootstraps your application.
It encourages you to do every bootstrapping in the main function instead of using
[frameworks doing magic](https://banzaicloud.com/blog/dependency-injection-go/) in the background.


## License

The MIT License (MIT). Please see [License File](LICENSE) for more information.
