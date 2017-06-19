# OpenTripPlanner-GBFS-Docker

Includes all the files to run an OTP server with tampa router. I had to remove portland as it had files larger than supported by github.

## Building the image

Run the following command from inside the directory where the the github repository was downloaded

`docker build -t <image-name> .`

## Running the image
When running the docker image include the parameters --server --autoScan. 
Example:

`docker run <image-name> --server --autoScan`
