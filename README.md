To Build the container Image and Run the container
 Go to app dircory and build the image with below command 
# docker build -t nodejs:1.0 .

To run the container with this image
# docker run -d -it --name node -p 80:3000 nodejs:1.0


