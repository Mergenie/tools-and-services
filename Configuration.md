# Configuration Tools and Services

## Compile Time Configuration

SaaS provider configurations such as CI, code coverage, release and versioning should be within the project code base. 
As an example, Travis-CI configuration file ".travis.yml" or Docker should be in the project root folder. 

## Runtime Configuration

Other then Spring Cloud Config Server, Vault and Kubernetes secrets(or Swarm/Docker secrets) can be used.
