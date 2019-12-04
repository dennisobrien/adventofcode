# adventofcode2019
Sharing my solutions to the adventofcode.com 2019 series.

# Running the notebook

I am using Jupyter notebooks for these challenge.

Build:
```
$ docker build -t dennisobrien/adventofcode2019:latest -f Dockerfile .
```

Run:
``` 
$ docker run -it -p 8888:8888 -v $(realpath .):/home/jovyan/workspace dennisobrien/adventofcode2019:latest
```

Copy the token and launch a browser and go to [http://localhost:8888/](http://localhost:8888/)
