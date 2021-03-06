# PropsProvider [![Build Status](https://travis-ci.org/trappar/props-provider.svg?branch=master)](https://travis-ci.org/trappar/props-provider)
React Component for passing props to dynamic children

## Introduction

The `PropsProvider` component primarily allows components to defer rendering details to their children. This allows for a higher degree of component reuse when those aspects are not intrinsically tied to each other.

This same concept already being used in many widely adopted libraries. For example, React Router v4 uses this idea to allow for [deferred rendering of links](https://react-router.now.sh/Link). The advantage to using this component is  standardization of the concept as well as additional functionality.

## Table of Contents

* [Installation](#installation)
* [Tutorial](docs/tutorial.md)
* [Usage](docs/usage.md)
* Examples
  * [Paginator](docs/example-paginator.md)
* [License](#license)

## Installation

Install as you would any other NPM dependency

```bash
npm install props-provider
```

## License

[![license](https://img.shields.io/badge/license-MIT-red.svg?style=flat-square)](Resources/meta/LICENSE)
