# bird

Bird is some training for Python and Docker.
I used VirtualBox, Ubuntu for all this process.

## required installations

To get the packages needed, required codes written in Terminal:

```bash
& sudo apt-get install python3
& pip3 install flask
```

## about Python file

For app.py to work in 80 port, getting permission to be root:
```bash
& sudo -s
%% entering computer password %%
```

## Requirements file

To run the application, building a container with the Flask for Dockerfile to rely on.


## dockerization

Dockerfile is available for these codes:

  -and the rest.

```bash
1. docker build -t application .
2. docker run -d -p 8080:80 application
