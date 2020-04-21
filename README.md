#flask-python is the docker file form which you generate the docker image and deploy it
#Build the image

docker build -t flask-python:latest .

#run the container:

docker run -d -p 5000:5000 flask-python
      
