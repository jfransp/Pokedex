# Pokedex
Pokédex app developed on top of the pokeapi.co REST API, with Retrofit, Room, Palette, Glide, Coroutines, Hilt and more, in MVVM architecture.

<p float="left"
align="center">
  <img src="https://github.com/jfransp/Pokedex/blob/master/mainscreen.jpg?raw=true" width="200" />
  <img src="https://github.com/jfransp/Pokedex/blob/master/savedscreen.jpg?raw=true" width="200" /> 
  <img src="https://github.com/jfransp/Pokedex/blob/master/detailsscreen.jpg?raw=true" width="200" />
</p>

# Libraries and Implementations
### Room
Persistence library
### Retrofit
Network requests
### Paging 3
Pagination of fetched data
### Coroutines
Concurrency tasks
### Dagger Hilt
Dependency injection
### Glide
Loading online images
### Palette
Custom and dynamic collor settings for views based on images
### GSON
Json parsing and converting
### SafeArgs Plugin
For passing basic data between fragments on navigation.
### Progress View
Custom progress view developed by [skydoves](https://github.com/skydoves) (from whom I also got inspiration for the detail screen layout).

# PokeAPI
This app was developed on top of the [pokeapi.co](https://pokeapi.co/) free to use pokemon data REST Api.

# Architecture
Basic MVVM architecture with repository. Remote mediation, when necessary, was handled within the viewmodel itself; dependencies were injected with Hilt; each fragment has
it's own viewmodel and some navigation dependent logic was implemented on the MainActivity itself.

There's still room for improvement as always but it works (:

###### App developed for the VentureLabs selective process code challenge.



