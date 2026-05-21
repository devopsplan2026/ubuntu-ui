# Create the image  

docker build -t ubuntu-ui .

# Run the container 

docker run -d --name ubuntu-ui -p 6901:6901 -p 5900:5900 ubuntu-ui

# Open in browser

http://localhost:6901/vnc.html?host=localhost&port=5900

# password

use secret