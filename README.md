#flask-python is the docker file form which you generate the docker image and deploy it
#Build the image

docker build -t flask-python:latest .

#run the container:

docker run -d -p 5000:5000 flask-python
      
      
      
     
     
***********************************

#AWS instance launch log

Your instances are now launching
The following instance launches have been initiated: i-0d55c7320ed483856 Hide launch log
Creating security groups
 
Successful (sg-0f0b65260a906f069)
Authorizing inbound rules
 
Successful
Initiating launches
 
Successful
Launch initiation complete
