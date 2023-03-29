# Cyberduck CLI Website

This is the development home for the [Cyberduck CLI](https://github.com/iterate-ch/cyberduck) [website](https://duck.sh).

## Requirements

```commandline
pip install 'pelican<4.0.0'
pip install 'fabric<2.0'
pip install minify
pip install pelican-minify
```

## Build

### Regenerate pages on changes

```commandline
invoke regenerate
```

### Run local web server

```commandline
invoke serve
```