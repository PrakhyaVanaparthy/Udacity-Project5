

## Settingup the Environment

1. Create a virtualenv and activate the environment
2. Run `Makefile` to install the necessary dependencies required for the project.
3. Additionaly install Hadolint,Minikube and Kubernetes.

### Running app.py in Docker and Kubernetes

1. Standalone:  `python app.py` 
2. Docker run:  `./run_docker.sh` (contains steps to build and run Docker image)
3. Dockerimage Upload : `./upload_docker.sh` (contains steps to upload docker image to docker hub)
4. Run in Kubernetes:  `./run_kubernetes.sh` (contains steps to run the docker image and forward port 8000 to 80)

