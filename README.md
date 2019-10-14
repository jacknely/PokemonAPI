# PokemonAPI
PokemonAPI for managing Pokemon

Performs a set of recipe operations on an imported recipe file
Allows you to get recipes by ID, get recipes by cuisine, and update existing recipes

## Requirements

- Python 3.7
- Flask


Install from requirements.txt


## Usage

Running the web app.

```
set FLASK_APP=run.py
flask run
```
Navigate to local host with recipe ID in order to see details of that recipe
```
http://127.0.0.1:5000/<id>
```


Navigate to recipe-by-cuisine with a specified cuisine.
Specify page number if desired
```
http://127.0.0.1:5000/cuisine/british/?page=1&items=1
```


Update existing recipes using a PUT request with the data to be updated for the corresponding ID.
```
eg
data = {"title": "changed"}
http://127.0.0.1:5000/<id>
```


