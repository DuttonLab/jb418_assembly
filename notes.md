# Canu assembly notes

## Installation

First, I cloned and installed canu.

```sh
KEVINs-MacBook-Pro-2:science ksb$ git clone git@github.com:marbl/canu.git
Cloning into 'canu'...
...
KEVINs-MacBook-Pro-2:science ksb$ cd canu/src/
KEVINs-MacBook-Pro-2:src ksb$ make -j 2
...
```

[See here](logs/canu_install.log) for install logs.

I also added `alias canu="/Users/ksb/computation/science/canu/Darwin-amd64/bin/canu"`
to my `~/.bash_profile` to make it easier to run the script.

## Data

I downloaded the following files from [google drive](https://drive.google.com/drive/folders/0B33EX5YdgPfIVWdaQXZMV1Mwb2c)
and moved them to a `raw_reads/` subfolder.
