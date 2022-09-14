# JUPYTER-Ultimate

Deployment in the catalog and configuration and in some cases the container image is maintained and updated by [davma.io](mailto:contact@davma.io)

</br>

<!-- ![https://github.com/davma-io](https://conocimientolibre.mx/wp-content/uploads/2019/11/ansible-glue-tools.png) -->
<img src="https://cdn3.f-cdn.com//files/download/93600166/Kubernetes%2C%20Ansible%2C%20Terraform%2C%20AWS_1.png?width=780&height=234&fit=crop" alt="drawing" width="600"/> 

</br> 

## This app will deploy a Jupyter instance with python 3.9 

__Jupyter Notebook is a web-based interactive computing platform.__

[![Build jupyter-ultimate](https://github.com/davma-io-images/jupyterlab/actions/workflows/jupyter-ultimate.yml/badge.svg)](https://github.com/davma-io-images/jupyterlab/actions/workflows/jupyter-ultimate.yml)
[![Update application to Napptive Playground](https://github.com/davma-io-templates/jupyter-templates/actions/workflows/jupiterA-napptive-push.yml/badge.svg)](https://github.com/davma-io-templates/jupyter-templates/actions/workflows/jupiterA-napptive-push.yml)
[![Docker Pulls](https://img.shields.io/docker/pulls/davma/jupyter-ultimate?logo=docker&logoColor=white)](https://hub.docker.com/r/davma/jupyter-ultimate)

## Pre-installed components

This image is a modification of the official [Jupyter Notebook Deep Learning Stack](https://hub.docker.com/r/jupyter/tensorflow-notebook) image. 

The following components have been added:

CLI Components
- Azure CLI
- AWS CLI
- Napptive CLI 

Infrastructure Components
- kubectl
- Terraform
- Ansible 

Python Components 
- Vault API client
- Pyodbc

__Important__ - This application is for development only, it is strongly recommended not to use it in production environments. It is not deployed with data persistence. For more info or help [contact](mailto:contact@davma.io)


## How to access to JUPYTER-Ultimate

Once the application has been deployed, open the public endpoint navigating through the web UI to select the application, selecting the Jupyter component, and clicking on the associated Endpoint. Alternatively with the CLI use:

```
playground apps open davmaio-jupyter
```

The davmaio-jupyterA instance automatically gets a public URL. If the application is APP_OK, copy the ingress link in your browser. 

```
https://davmaio-jupyterult-<active-namespace>.apps.playground.napptive.dev
```

- We need a token to log into the page. We can obtain the token checking the application logs:


## References
* https://jupyter.org/
* https://docs.ansible.com/
* https://www.terraform.io/intro
* https://docs.jupyter.org/en/latest/index.html
* https://hub.docker.com/r/davma/jupyter-ansible-tf

</br>
</br>
</br>

![https://github.com/davma-io](https://davma.io/wp-content/uploads/2022/05/davma.io6_-e1659187814635.png)
</br>
</br>
</br>