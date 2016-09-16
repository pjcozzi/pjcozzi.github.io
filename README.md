http://www.seas.upenn.edu/~pcozzi/

Personal website for projects, books, talks, courses taught, etc.

## Build

### 1. Install docker
### 2. Build docker image

```
docker build -t blog /path/to/your/project
```

### 3. Run container

```
docker run -d --name blog1 -p 4000:4000 -v /path/to/your/project:/working blog
```

### 4. Broswer

```
http://localhost:4000
```

## Add data

- Add your data in _data/*.yml file.
