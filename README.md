# data-science-intro notebook

This is a docker container running jupyter notebook and connects to a local persistent folder
To start notebook as a docker container - use this :

## clone the repository into a new folder
```
~/ git clone git@github.com:chenchuk77/data-science-intro.git
```

# run a docker container pointing to the cloned repo
```
~/ docker run -d -p 8888:8888 -v $(pwd):/home/ds/notebooks dataquestio/python3-starter
```
# open chrome/firefox
```
http://localhost:8888/tree
```
