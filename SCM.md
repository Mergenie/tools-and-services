# Source Code Management Tools and Services

## Tool

Git is the version control tool, projects may follow git-flow if it is relevant. 


## Service

[GitHub](https://github.com/) is the SCM service for all projects. Source projects should follow 
either github flow or gitflow. Since source projects should follow semantic versioning and avoid snapshots,
in both cases there should be pull request webhook that checks if the version for that project is updated 
according to semver. 


The semver control project should be deployed on cloud and should be available as a 
webhook integration for github(and in the future for gitlab, bitbucket, jenkins etc.). 

![semver controlled pull request](https://raw.githubusercontent.com/Mergenie/tools-and-services/master/SemverControlProject.png "semver controlled pull request")
