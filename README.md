#Build the image

docker build -t flask-python:latest .

#run the container:

docker run -d -p 5000:5000 flask-python 
