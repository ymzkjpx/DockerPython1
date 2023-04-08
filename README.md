# What is this?
A very very simple sample application using Docker and Python.

# What can you do?
The words "Hell Python" can be displayed on the web browser.

# Build
```bash
$ docker build -t myapp .
```

# Run App
```bash
$ docker run -p 5000:5000 myapp
```

# Stop App
```bash
Ctrl + c
```

# Stop Command
```bash
docker stop $(docker ps -q --filter ancestor=myapp)
```

# License

