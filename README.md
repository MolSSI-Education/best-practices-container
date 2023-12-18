### How to build Docker image 


## Build/Run Docker image for Molssi Python Best practices workshop 
The dockerfile can be used to build a docker image. Clone this repository and navigate using the command line (a terminal) to the root folder of the repository.
Run the following command to build the docker image:
`docker build -t python-best-practices-container .`
After it has been built, you can run the resulting image as an interactive terminal using
`docker run -it python-best-practices-container`

The repository also has a pre-built image that can be pulled to your local computer using Docker.
The container can be found in the packages section of this repository, or pulled using:
`docker pull ghcr.io/molssi-education/python-best-practices-container:latest`
Once the image is stored locally, you can the following command to run the image as if you had built it.
`docker run -it ghcr.io/molssi-education/python-best-practices-container:latest`
