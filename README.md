# ULX Unofficial Documentation

**Read the documentation on https://timmy.github.io/ulx-docs/.**

[ULX v3](https://github.com/teamulysses/ulx) has no official reference documentation. Looking for information on ULX often yields outdated, low-quality or irrelevant results. The goal of this project is to provide users of ULX with a reliable resource.

## Contributing

You can help improve the documentation!

- [Open an issue](https://github.com/Timmy/ulx-docs/issues/new) to report an error or make a suggestion.
- [Create a pull request](https://github.com/Timmy/ulx-docs/issues/new) to propose changes to the documentation.

## Building

These build instructions will help you set up a local version of the site.

#### Requirements

This project uses Bundler to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler, you must install Ruby.

- [Ruby](https://www.ruby-lang.org) (2.1.0 or higher)
- [Bundler](https://bundler.io)

#### Installation

1. `git clone https://github.com/Timmy/ulx-docs.git` - Download the repository to your computer.
1. `cd ulx-docs` - Change the working directory to the project root.
1. `bundle install` - Install Jekyll and other dependencies.

#### Run local site

1. `bundle exec jekyll serve -b ""` - Build the site and serve it locally.
1. Open `http://localhost:4000` in your browser.
