# alexjohnson.io

Hugo-powered [alexjohnson.io](alexjohnson.io)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Installing

[Hugo Quick Start](https://gohugo.io/getting-started/quick-start/)

### Submodules

This site is based on [Hugo Story](https://github.com/caressofsteel/hugo-story)

Add the theme submodule with:

```sh
$ git submodule add https://github.com/caressofsteel/hugo-story.git themes/hugo-story
````

### Running Web Server

Once you have installed local dependencies, start a local web server with:

``` sh
$ hugo server
```

Your local web server should now be running at ``localhost:1313``

### Building

Build the site with:

```sh
$ hugo -D
````

### Deploying

We use Amazon S3 for storing our static files. See the alexjohnson.io bucket. Credentials in 1Password.

To upload to Amazon S3, we recommend [Cyberduck](https://cyberduck.io/) or [3Hub](https://apps.apple.com/us/app/3hub/id427515976?mt=12).

## Resources

### Built With

* [Bootstrap](http://getbootstrap.com/)
* [Hugo](https://gohugo.io/)

### Contributors

* Alex Johnson -[@alexjohnson505](https://github.com/alexjohnson505)
