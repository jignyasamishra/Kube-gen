# Kube-gen
A Go-based command-line tool for creating Kubernetes deployment configurations.
## Features

- Generate Kubernetes deployment YAML files with ease.
- Customizable deployment parameters such as name, image, replicas, and port.
  
## Installation

To install Kubegen, clone this repository and build the binary:

- `git clone https://github.com/jignyasamishra/Kube-gen.git`
- `cd kubegen`
- `go build -o kubegen`


## Usage

After building the binary, you can run Kubegen with the following command:

 `./kubegen --name myapp --image myrepo/myapp:latest --replicas 3 --port 8080 > myapp-deployment.yaml`


This will generate a Kubernetes deployment YAML file named `myapp-deployment.yaml` with the specified name, image, number of replicas, and port.

## Flags

- `-n, --name`: The name of the deployment.
- `-i, --image`: The Docker image to deploy. 
- `-r, --replicas`: The number of replicas to deploy. 
- `-p, --port`: The port the container should listen on. 



## License

This project is licensed under the MIT License. See the LICENSE file for details.
