# nix-python-simple

## What's here

A very simple python environment, with Nix for package management. You can see
in the [flake.nix](./flake.nix) file where to specify python dependecies.

For a more "production-ready" Python envrionment, you should look at
[nix-python-uv](https://github.com/InvariantClub/nix-python-uv).


## What's possible

### Hacking on python with the libraries available

``` sh
python
...
>>> import pandas
```

or

``` sh
jupyter notebook
...
```
