[![Latest Version](https://img.shields.io/github/tag/olivertappin/rename.svg?style=flat&label=release)](https://github.com/olivertappin/rename/tags)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat)](LICENSE.md)
[![GitHub issues](https://img.shields.io/github/issues/olivertappin/rename.svg)](https://github.com/olivertappin/rename/issues)

# Rename
Rename multiple files with numbered endings

## About

Rename is a simple bash script to help rename a large number of files to a human-readable file name.
This works particullary well for renaming images that have come directly from your digital camera.

For example, you can change the names generated from your digital camera to human-readable names of your choice:

```
0C0A1507.jpg => Summer Holiday 1.jpg
0C0A1508.jpg => Summer Holiday 2.jpg
0C0A1509.jpg => Summer Holiday 3.jpg
```

## Installation

```bash
cd ~/Desktop
wget https://github.com/olivertappin/rename/archive/master.zip
unzip master.zip
mv rename-master rename
cd rename
```

## Usage

```bash
cp -R /path/to/files/* ~/Desktop/unnamed
./rename
```

For those less-familar with the command line, you can open the project directory and simply click on the `run.command` file.

## Options

During execution, the script will ask you the following questions:

- Please enter the file name
- Please enter the separator (leave blank for a space)

The first will be the equivilent of 'Summer Holiday' in the example above.
The second is the character between 'Summer Holiday' and the number. In the example above, this is a space, but this could be anything.

