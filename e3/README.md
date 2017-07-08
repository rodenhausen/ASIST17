# e3

## Setup of e3
In the following, three alternative ways to setup and use e3 are described. The order is from most to least convenient.
1. Jupyterhub
   1. [Create an issue](https://github.com/EulerProject/e3-jupyterhub/issues) stating your github username and the wish to have an account created. Wait for response from an admin on the created issue. 
   2. [Visit Jupyterhub @ eyeofjupyter.org](https://eyeofjupyter.org/)
   3. Optionally organize your input files via new file/folder or file upload.
   3. Create a new e3 notebook (or other, depending on your preference), to run e3 commands.
2. Docker image
   1. [Install docker](https://docs.docker.com/engine/installation/)
   2. Run `docker run rodenhausen\e3-docker-image`
   3. Run e3 commands in the container
3. Manual installation
   1. [Setup e3](https://github.com/EulerProject/e3/blob/master/README.md)

## Run the timezone use cases
- To replay the use cases CEN vs NDC and CEN vs TZ use cases of the paper please refer to the [IPython notebook](https://github.com/rodenhausen/ASIST17/blob/master/e3/notebook.ipynb) that contains all the steps and explanations

- You can find output of running the e3 commands directly in the [IPython notebook](https://github.com/rodenhausen/ASIST17/blob/master/e3/notebook.ipynb) as well as in [e3's workspace](https://github.com/rodenhausen/ASIST17/blob/master/e3/e3_data). In the workspace you will for example find a [HTML file](https://github.com/rodenhausen/ASIST17/blob/master/e3/e3_data/index.html) that can be used to [render the history](https://htmlpreview.github.io/?https://github.com/rodenhausen/ASIST17/blob/master/e3/e3_data/index.html) of the commands run. You can drill down on nodes in the history by double clicking. 

- [e3's state](https://github.com/rodenhausen/ASIST17/blob/master/e3/.e3) is also contained for completeness. For more information on this see [e3](https://github.com/EulerProject/e3).

## Learn more
If you want to learn more about  all the features of e3 please refer to the [e3-demos](http://github.com/EulerProject/e3-demos)
