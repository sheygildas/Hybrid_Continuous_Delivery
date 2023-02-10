
# Project-13
## :ledger: Index

- [About The Project](#beginner-about-the-project)
- [Problem that this project solves ](#question-problem-that-this-project-solves)
- [Solution to the problem.](#key-solution-to-the-problem)
- [Tools](#hammer_and_wrench-Tools)
- [Architecture of this project](#house-architecture-of-this-project)
- [Steps to execute the project](#zap-steps-to-execute-the-project)
  - [Continuous Integration Setup](#package-continuous-integration-setup)
  - [Login to AWS Account ](#key-login-to-aws-account)
  - [RDS SG](#package-rds-sg)
  - [Beanstalk and RDS Setup](#package-beanstalk-and-rds-setup)
  - [RDS Initialization and SG update](#package-rds-initialization-and-sg-update)
  - [ElasticCache and Active MQ](#package-elasticcache---and-active-mq)
  - [Cloud Token](#package-cloud-token)
  - [Sonar Cloud Integration with Jenkins](#package-sonar-cloud-integration-with-jenkins)
  - [Sonar Cloud Token](#package-sonar-cloud-token)
  - [Sonar.organization in properties file](#package-sonarorganization-in-properties-file)
  - [Sonar Cloud Scanning Job](#package-sonar-cloud-scanning-job)
  - [IAM User for Jenkins authorization](#package-iam-user-for-jenkins-authorization)
  - [CodeBuild policy](#package-codebuild-policy)
  - [S3 bucket policy](#package-s3-bucket-policy)
  - [Update Bean URL in Parameter Store for CodeBuild job](#package-update-bean-url-in-parameter-store-for-codebuild-job)
  - [Deploy to Beanstalk Job](#package-deploy-to-beanstalk-job)
  - [Software Testing Job with AWS Code Build](#package-software-testing-job-with-aws-code-build)
  - [Plugin](#package-plugin)
  - [Job Setup](#package-job-setup)
  - [Changes in CodeBuild](#package-changes-in-codebuild)
  - [Update Buildspec file](#package-update-buildspec-file)
  - [Store URL variable in Parameter store](#package-store-url-variable-in-parameter-store)
  - [Connect all jobs in Jenkins Pipeline](#package-connect-all-jobs-in-jenkins-pipeline)
  - [Test](#package-test)
  - [Prod Deploy Job](#package-prod-deploy-job)
- [Verify from browser](#earth_africa-verify-from-browser) 
- [Resources](#page_facing_up-resources)
- [Credit/Acknowledgment](#star2-creditacknowledgment)


## :beginner:About The Project

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

## :question: Problem that this project solves 

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

## :key: Solution to the problem.

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

## :hammer_and_wrench: Tools
- A tool
- B tool

| Name | Description |
| --- | --- |
| [`@toast-ui/editor-plugin-chart`](https://github.com/nhn/tui.editor/tree/master/plugins/chart) | Plugin to render chart |
| [`@toast-ui/editor-plugin-code-syntax-highlight`](https://github.com/nhn/tui.editor/tree/master/plugins/code-syntax-highlight) | Plugin to highlight code syntax |
| [`@toast-ui/editor-plugin-color-syntax`](https://github.com/nhn/tui.editor/tree/master/plugins/color-syntax) | Plugin to color editing text |
| [`@toast-ui/editor-plugin-table-merged-cell`](https://github.com/nhn/tui.editor/tree/master/plugins/table-merged-cell) | Plugin to merge table columns |
| [`@toast-ui/editor-plugin-uml`](https://github.com/nhn/tui.editor/tree/master/plugins/uml) | Plugin to render UML 

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>


## :beginner: Architecture of this project.

![Project Image](project-image-url)

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

## :zap: Steps to Execute the project. 

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>


### :package: Continuous Integration Setup


<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :key: Login to AWS Account

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>



### :package: RDS SG

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Beanstalk and RDS Setup


<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: RDS Initialization and SG update


<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: ElasticCache   and Active MQ 

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Cloud Token

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Sonar Cloud Integration with Jenkins

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: Sonar Cloud Token

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: Sonar.organization in properties file

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Sonar Cloud Scanning Job

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: IAM User for Jenkins authorization

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: CodeBuild policy

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: S3 bucket policy

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Update Bean URL in Parameter Store for CodeBuild job

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Deploy to Beanstalk Job

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Software Testing Job with AWS Code Build

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: Plugin

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: Job Setup

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Changes in CodeBuild

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: Update Buildspec file

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

#### :package: Store URL variable in Parameter store

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Connect all jobs in Jenkins Pipeline

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Test

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

### :package: Prod Deploy Job


## :earth_africa: Verify from browser

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>


## :page_facing_up: Resources

<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>


## :star2: Acknowledgment


<br/>
<div align="right">
    <b><a href="#Project-13">↥ back to top</a></b>
</div>
<br/>

