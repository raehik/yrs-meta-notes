CKAN exposes an API to inspect the registry of open data sets they have.
That means I could use data on datasets, and perhaps even use data from any
of the datasets available. I could present data about datasets, or use data
about datasets in a game.

I want the program to:
    - use the dataset metadata in some way (e.g. author, set name)
    - request arbitrary data from a random dataset
The latter requires that CKAN exposes information about how to access each
dataset.

- I want the program to be able to request data from hopefully any of the
  datasets returned.
