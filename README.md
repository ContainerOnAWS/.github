# AWS container sample projects for EKS, ECS, and App Runner

## Objectives

* Compare the differences among AWS container services and IaC tools with the sample code from infrastructure provisioning and deployment.
* The contents will help you to choose the right service for your environment.

## Container sample project repositories

### EKS

| Repository                                                               | Time To Complete | Description          |  SonarQube  |
|--------------------------------------------------------------------------|------------------|----------------------|----------------------|
| [eks-cdk-blueprints](https://github.com/ContainerOnAWS/eks-cdk-blueprints)      | 30m | EKS cluster, managed node group, and add-on with EKS Blueprints. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-blueprints-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-blueprints-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-blueprints-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-blueprints-cdk) |
| [eks-cdk](https://github.com/ContainerOnAWS/eks-cdk)                            | 30m | EKS cluster and managed node group with CDK.        | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-cdk)  [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-cdk)    |
| [eks-eksctl](https://github.com/ContainerOnAWS/eks-eksctl)                      | 30m | EKS cluster and managed node group with eksctl.     |  [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-eksctl&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-eksctl) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-eksctl&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-eksctl)  |
| [eks-terraform](https://github.com/ContainerOnAWS/eks-terraform)                | 30m | EKS cluster and managed node group with Terraform.  |    |
| [eks-gpu-autoscaling](https://github.com/ContainerOnAWS/eks-gpu-autoscaling)    | 1h+ | GPU auto scaling based on Prometheus custom metric. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-gpu-autoscaling&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-gpu-autoscaling) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_eks-gpu-autoscaling&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_eks-gpu-autoscaling)   |
| [eks-gpu-cloudwatch](https://github.com/ContainerOnAWS/eks-gpu-cloudwatch)      | TBD | GPU metric CloudWatch exporter.                      |    |

### ECS

| Repository                                                     | Time To Complete  | Description          | SonarQube  |
|----------------------------------------------------------------|-------------------|----------------------|---------------------|
| [ecs-fargate-cdk](https://github.com/ContainerOnAWS/ecs-fargate-cdk)  | 8m  | RESTful API autoscaling with ECS Fargate and CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_ecs-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_ecs-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_ecs-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_ecs-fargate-cdk)   |
| [ecs-ec2-cdk](https://github.com/ContainerOnAWS/ecs-ec2-cdk)          | 15m | RESTful API autoscaling with ECS EC2 and CDK.     | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_ecs-ec2-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_ecs-ec2-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_ecs-ec2-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_ecs-ec2-cdk) |
| [ecs-gpu-cdk](https://github.com/ContainerOnAWS/ecs-gpu-cdk)          | 20m | Inference RESTful API autoscaling with ECS GPU EC2 and CDK.   | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_ecs-gpu-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_ecs-gpu-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_ecs-gpu-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_ecs-gpu-cdk) |

### App Runner

| Repository                    | Time To Complete  | Description          |
|-------------------------------|-------------------|----------------------|
| [cdk-apprunner](https://github.com/ContainerOnAWS/cdk-apprunner)  | TBD  | TBD |

## DevOps

| Repository                    | Time To Complete  | Description          |  SonarQube  |
|-------------------------------|-------------------|----------------------|---------------------|
| [jenkins-fargate-cdk](https://github.com/ContainerOnAWS/jenkins-fargate-cdk)  | 7m | Build a Jenkins on Fargate with CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_jenkins-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_jenkins-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_jenkins-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_jenkins-fargate-cdk) |
| [sonarqube-fargate-cdk](https://github.com/ContainerOnAWS/sonarqube-fargate-cdk)  | 12m | Build a continuous inspection system for code quality on Fargate with SonarQube and CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_sonarqube-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_sonarqube-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_sonarqube-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_sonarqube-fargate-cdk) |
| [jenkins-sonarqube-fargate-cdk](https://github.com/ContainerOnAWS/jenkins-sonarqube-fargate-cdk)  | TBD | Build Jenkins and Sonarqube on Fargate with CDK. | [![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_jenkins-sonarqube-fargate-cdk&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_jenkins-sonarqube-fargate-cdk) [![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=ContainerOnAWS_jenkins-sonarqube-fargate-cdk&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=ContainerOnAWS_jenkins-sonarqube-fargate-cdk) |


## Architecture

<img src="https://github.com/ContainerOnAWS/cdk-eks-blueprints/blob/develop/screenshots/diagram.png?raw=true"/>

<img src="https://github.com/ContainerOnAWS/ecs-fargate-cdk/blob/develop/screenshots/fargate-architecture.png?raw=true"/>

<img src="https://raw.githubusercontent.com/ContainerOnAWS/jenkins-sonarqube-fargate-cdk/develop/screenshots/architecture.png"/>