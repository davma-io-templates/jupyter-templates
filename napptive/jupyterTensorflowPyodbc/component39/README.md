# davma.io JUPYTER-TENSORFLOW

<!-- ![https://github.com/davma-io](https://www.gstatic.com/devrel-devsite/prod/v0e5fe81d770a1c83a74ae94cff5f78c2b690ac595b30fc2439f12b56fdf9fe78/tensorflow/images/lockup.svg) -->
<img src="https://www.gstatic.com/devrel-devsite/prod/v0e5fe81d770a1c83a74ae94cff5f78c2b690ac595b30fc2439f12b56fdf9fe78/tensorflow/images/lockup.svg" alt="drawing" width="600"/>

This app will deploy a Jupyter instance with python 3.9, tensorflow and pyodbc 4.0.30 pre-installed

[![Build and push images](https://github.com/davma-io-images/jupyter-tensorflow-pyodbc/actions/workflows/docker-image.yml/badge.svg)](https://github.com/davma-io-images/jupyter-tensorflow-pyodbc/actions/workflows/docker-image.yml)

[![Update application to Napptive Playground](https://github.com/davma-io-templates/jupyter-templates/actions/workflows/jupiterTF-napptive-push.yml/badge.svg)](https://github.com/davma-io-templates/jupyter-templates/actions/workflows/jupiterTF-napptive-push.yml)

[![Docker Pulls](https://img.shields.io/docker/pulls/davma/jupyter-tensorflow-pyodbc?logo=docker&logoColor=white)](https://hub.docker.com/r/davma/jupyter-tensorflow-pyodbc)   

Jupyter Notebook is a web-based interactive computing platform.

> This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. For more info or help [contact](mailto:contact@davma.io)


## How to access to JUPYTER-TENSORFLOW

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Jupyter component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-jupyter
```

The davmaio-jupyter instance automatically gets a public URL. If the application is APP_OK, copy the ingress link in your browser. 

```
https://davmaio-jupyter39-<active-namespace>.apps.playground.napptive.dev
```

- We need a token to log into the page. We can obtain the token checking the application logs:


## References
* https://jupyter.org/
* https://docs.jupyter.org/en/latest/index.html
* https://hub.docker.com/r/davma/jupyter-tensorflow-pyodbc

</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>