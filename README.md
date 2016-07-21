PokemonGo Map pip installer
===========================

This is a [PokemonGo Map](https://github.com/AHAAAAAAA/PokemonGo-Map) installer.

## Install

You can install PokemonGo Map by just using pip

```
pip2 install -e git+https://github.com/Darkade/pokemongo-map-pip.git#egg=pokemongo-map-pip
```

## Usage

This installs the runserver.py to your PATH as `pokemap` So you could use it like this

```
pokemap -st <step count> -l <location> -u <ptc user> -p <ptc password> -dg
```

To learn more about how to use the PokemonGo Map you can go to [their wiki](https://github.com/AHAAAAAAA/PokemonGo-Map/wiki)

## Caveats

You may need to copy your `credentials.json` to `src/pokemongo-map-pip/PokemonGoMap/credentials.json`
