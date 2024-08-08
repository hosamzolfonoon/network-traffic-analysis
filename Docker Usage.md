** **Docker Usage** **

As a reader of this notebook, images would be shown correctly. Accordingly, in the following link discriptions and images are shared in a pdf file.

https://drive.google.com/file/d/1SmndHWLj_Kq2FRSjc1d3KyJSFw94AGmS/view?usp=sharing

**1-Pulling the Docker Image**

To get the Docker image from DockerHub, use the following command:

# docker pull hosamzolfonoon/network-traffic-analysis:1.0

**2-Running Container Image**

After pullin run it in interactive mode while exposing ip:

# docker run -ip 8888:8888 -it network-traffic-analysis:1.0

**3-Running the Associated Notebook**

Use the following commmand to run jupyter notebook on your browser:

# jupyter notebook --ip=0.0.0.0 --no-browser --allow-root

