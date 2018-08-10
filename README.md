# Heroku buildpack: opus

This is a Heroku buildpack for using lib opus in your project.

# Usage

For a new project:

``` sh 
$ heroku create --buildpack https://github.com/frostlight/opus-buildpack
```

If it is an existing project, just do:

``` sh 
$ heroku buildpacks:set https://github.com/frostlight/opus-buildpack
```

The library files will be in "vendor/lib".
