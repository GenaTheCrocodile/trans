# Trans

Trans is a dependency-free CLI for Google Translate

## Installation
```bash
git clone https://github.com/GenaTheCrocodile/trans.git
cd trans
chmod +x trans
./trans "Hello World" es
```
You need to have the [Python](https://www.python.org/) interpreter installed on your system

## Usage

```
usage: trans [-h] [-sl SL] [-l] text tl

positional arguments:
  text              source text / word
  tl                translation language

optional arguments:
  -h, --help        show this help message and exit
  -sl SL            source language (auto by default)
  -l, --list-codes  list all language codes
```
## Usage example
```bash
$ trans "Hello, World!" es
¡Hola Mundo!

$ trans "Hello, World!" es -sl en # Set the source language manually 
¡Hola Mundo!

$ trans -l
af - afrikaans
sq - albanian
am - amharic
...
```

## License
[MIT](https://choosealicense.com/licenses/mit/)