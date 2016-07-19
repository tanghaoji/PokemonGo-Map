<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/1760334/16904125/5621e800-4c4d-11e6-9906-55cfd778fd27.png">
</p>

# PokemonGo Map
Live visualization of all the pokemon in your area, building off [Mila432](https://github.com/Mila432/Pokemon_Go_API)'s PokemonGo API, [tejado's additions](https://github.com/tejado/pokemongo-api-demo), [leegao's additions](https://github.com/leegao/pokemongo-api-demo/tree/simulation) and [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps). Proof of concept that we can load all the pokemon visible nearby given a location.

Currently really rough, shows duplicate pokemon and requires refreshing page a lot (until the PokemonGo servers decide we're worthy). However, it works. Be warned, ugly ugly code ahead.

Team icons from [israelvicars](https://github.com/israelvicars/pkmn-go-emoji).

# Installation
`pip install -r requirements.txt`

# Usage
`python example.py -u myUsername -p myPassword -l "Boulder, CO" -st 5`

-st: steps to take

-l: location, anything that Google Maps understands.

# FAQ

* Do I need Python 2.7? Yes! Can I use Python 3.x? No!

* Can I sign in with Google? Not yet, we're working on it, until then get a Trainer Club account

* I'm on Windows, why does nothing work? See if anything in https://www.reddit.com/r/pokemongodev/comments/4t80df/wip_pokemon_go_map_visualization_google_maps_view/d5feu2f helps
