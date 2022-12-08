## Getting Started

### Prerequisites

* Python 3.7+
* Anaconda 4+ (optional)
* Python modules from the `requirements.txt`

### Deployment

Dowload and install the dependencies with the command:

```
$ python -m pip install -r requirements.txt
```


```
$ python rmovie.py "MOVIE TITLE"
```

You can also specify the year in which the movie was released, in this case, you have to put the year in brackets in the same first argument:
```
$ python rmovie.py "MOVIE TITLE (YEAR)"
```

* Works with any case (lower or upper)
* The word "the" is always ignored
* You can put the year of the movie inside brackets like: (2020)

Valid request examples:

```
$ python rmovie.py "Shawshank Redemption"
$ python rmovie.py "lord of the rings"
$ python rmovie.py "STAR WARS"
$ python rmovie.py "STAR WARS (1977)"
$ python rmovie.py "tOy StOrY"
```

