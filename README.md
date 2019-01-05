# Heroku buildpack: opus

This is a Heroku buildpack for using lib opus in your project.

# Usage

For a new project:

``` sh 
$ heroku create --buildpack https://github.com/Hitsounds/Opus-Buildpack
```

If it is an existing project, just do:

``` sh 
$ heroku buildpacks:set https://github.com/Hitsounds/Opus-Buildpack
```

The library files will be in "vendor/lib".
