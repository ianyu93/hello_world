# Hello World

Says Hello to the world!

## Getting started

To run this repository, you will need to install [Poetry](https://github.com/python-poetry/poetry), a popular dependencies 
and virtual environments' manager for Python.

Once you have that, run the following commands:
```sh
git clone git@github.com:sam1902/hello_world.git hello_world
cd hello_world
poetry install
poetry run python3 hello_world/eval/eval.py --help
```

## Usage
```
usage: eval.py [-h] [-o OUTPUT] [-i INT_PARAM]
               [--float_param_optional FLOAT_PARAM_OPTIONAL] [-v]
               input

Says Hello to the world!

positional arguments:
  input                 Input dataset

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT, --output OUTPUT
                        Where to write the output
  -i INT_PARAM, --int_param INT_PARAM
                        Cool int param.
  --float_param_optional FLOAT_PARAM_OPTIONAL
                        Cool optional float param.
  -v, --verbose         Displays helpful information along.

```
