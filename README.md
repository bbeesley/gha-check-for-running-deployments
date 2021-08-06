# gha-check-for-running-deployments

A simple action to check for running CodeDeploy deployments


## Options

| name                       | description                                       | required | default      |
|----------------------------|---------------------------------------------------|----------|--------------|
|  region                    | AWS region to count deployments in                | false    | eu-central-1 |
|  application-name          | The CodeDeploy application name                   | true     |              |
|  deployment-group-name     | The CodeDeploy deployment group name              | true     |              |
|  deployment-status         | Count deployments with this status                | true     | InProgress   |


## Requirements

Needs AWS authentication
