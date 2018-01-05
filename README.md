# Sketchbook

Sketchbook enhances available Git commands to support storing Sketch files in human readable format (JSON). Sketchbook configuration takes advantage of Git LFS to store bitmaps included in Sketch files (.png, .jpg, .gif).


## Installation

1. Download or clone this project
2. Reference .bash-sketchbook in your .bash-profile

## Usage

### Create project
Creates new local repository and a remote one on GitHub.

```
sketchbook new
```

### Clone project
Clones existing remote repository into current working directory.

```
sketchbook clone
```

### Push changes
Adds, commits and pushes project files into a remote repository.

```
sketchbook push
```

### Pull changes
Pulls changed files from a remote repository.

```
sketchbook pull
``` 


## Other commands

### Initialise repository
Initialises a repository for an existing project.

```
sketchbook init
```

### Connect repositories
Connects existing local repository with a remote one.

```
sketchbook connect
```


## License
[MIT](http://opensource.org/licenses/MIT)