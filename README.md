# Sketchbook

Sketchbook enhances available Git commands to support storing Sketch files in human readable format (JSON). Configuration takes advantage of Git LFS to store bitmaps included in Sketch files (.png, .jpg, .gif).


## Installation

1. Download or clone this project
2. Reference .bash-sketchbook in your .bash-profile

## Usage

### Create project

```
sketchbook new
```
Creates new local repository and a remote one on GitHub.

### Clone project

```
sketchbook clone
```
Clones existing remote repository into current working directory.

### Push changes

```
sketchbook push
```
Adds, commits and pushes project files into a remote repository.

### Pull changes

```
sketchbook pull
``` 
Pulls changed files from a remote repository.

## Other commands

### Initialise repository

```
sketchbook init
```
Initialises a repository for an existing project.

### Connect repositories

```
sketchbook connect
```
Connects existing local repository with a remote one.

## License
[MIT](http://opensource.org/licenses/MIT)