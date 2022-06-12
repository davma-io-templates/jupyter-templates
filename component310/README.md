# davma.io JUPYTER-TENSORFLOW

This app will deploy a Jupyter instance with python 3.10, tensorflow and pyodbc 4.0.30 pre-installed

[![Build and push images](https://github.com/davma-io-images/jupyter-tensorflow-pyodbc/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/jupyter-tensorflow-pyodbc/actions/workflows/docker-image.yml)

> This application is for development only, it is strongly recommended not to use it in production environments.

Jupyter Notebook is a web-based interactive computing platform.


## How to access to JUPYTER-TENSORFLOW

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Jupyter component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-jupyter-tensorflow:<version>
```

The davmaio-jupyter instance automatically gets a public URL. If the application is APP_OK, copy the ingress link in your browser. 

```
https://davmaio-jupyter-<active-namespace>.apps.playground.napptive.dev
```

- We need a token to log into the page. We can obtain the token checking the application logs:


## References
* https://jupyter.org/
* https://docs.jupyter.org/en/latest/index.html
* https://hub.docker.com/r/davma/jupyter-tensorflow-pyodbc