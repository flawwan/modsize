# modsize.py

A tool used to change the image size of an image. Currently only .png files are supported. 


## Usage

```bash
./modsize.py --help
usage: modsize.py [-h] [--width WIDTH] [--height HEIGHT] file output

positional arguments:
  file                  Filepath to image
  output                Filepath to image

optional arguments:
  -h, --help            show this help message and exit
  --width WIDTH, -sw WIDTH
                        New width of image
  --height HEIGHT, -sh HEIGHT
                        New height of image
```

## Install

* pip install -r requirements.txt
* [pngcsum](http://schaik.com/png/pngcsum.html)

## Examples

Image file from X-MAS CTF 2018

```bash
$ ./modsize.py "examples/celeb.png" out.png
```
