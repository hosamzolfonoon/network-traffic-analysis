** **Docker Usage** **


**1-Pulling the Docker Image**

To get the Docker image from DockerHub, use the following command:

*docker pull hosamzolfonoon/network-traffic-analysis:1.0*

**2-Running Container Image**

After pullin run it in interactive mode while exposing ip:

*docker run -ip 8888:8888 -it network-traffic-analysis:1.0*

**3-Running the Associated Notebook**

Use the following commmand to run jupyter notebook on your browser:

*jupyter notebook --ip=0.0.0.0 --no-browser --allow-root*

