# bird

Bird is some training for Python and Docker.
I used Python, Flask Framework for all this process in Ubuntu.

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

To finish dockerization:

```bash
& docker build -t application .
& docker run -d -p 8080:80 application
```

Visiting http://0.0.0.0:8080 on a browser will show the output.
