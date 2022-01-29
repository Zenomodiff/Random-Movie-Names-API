# Random-Movie-Names-API 🎞️📽️🎬📼

+ An API that will return random Movie Names 💽📹🎦
+ Dedicated To All Movie Lovers ❤️

## Usage:

+ ### [`https://randommovienameapi.herokuapp.com`](https://movie-names-api.herokuapp.com) to get the documentation.
+ ### [`https://randommovienameapi.herokuapp.com/api/Movie-Names/all`](https://movie-names-api.herokuapp.com/api/Movie-Names/all) to get all the Movie Names at once.
+ Change `all` to parameter `?number=` to specify the number of Movie Names you want to receive.
+ Change `all` to parameter `?index=` to specify the index of the Movie Name you are targeting.

This project is hosted on [Heroku](https://www.heroku.com/) with zenomodiffofficial@gmail.com

## Rebuild the project:
+ Clone the repo.
+ Run `python -m venv .env` to create a virtual environment.
+ Run `source .env/bin/activate` to activate the virtual environment.
+ Run `pip install requirements.txt`.
+ Run `python app.py`.
+ App starts at `http://localhost:5000` by default, but can be configured with a `.env` file. 

## Example:

+ ### [`https://randommovienameapi.herokuapp.com/api/Movie-Names?number=1`](https://randommovienameapi.herokuapp.com/api/Movie-Names?number=1) returns: ↓
```JSON
[
  {
    "Movie_Name": "Conjuring"
  }
]
```

+ ### [`https://randommovienameapi.herokuapp.com/api/Movie-Names?number=2`](https://randommovienameapi.herokuapp.com/api/Movie-Names?number=2) returns: ↓
```JSON
[
  {
    "Movie_Name": "Gladiator"
  }, 
  {
    "Movie_Name": "Titanic"
  }
]
```
