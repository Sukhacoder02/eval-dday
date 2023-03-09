# End to End Evaluation

# Cloning the Repo

### As this is a repo with submodules, you need to clone it recursively with `--recursive` flag enabled.

```
git clone --recursive git@github.com:Sukhacoder02/eval-dday.git
```

# If you have already cloned the repo, you can update the submodules with

```
git submodule update --init --recursive
```

### Build the compose file as 
```
  docker-compose build
```

### Run the compose file as 
```
  docker-compose up
```

### Alternatively, build and run the compose at the same time as 
```
  docker-compose up --build
```
