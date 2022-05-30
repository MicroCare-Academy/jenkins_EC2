# jenkins_EC2

http://ec2-52-66-238-76.ap-south-1.compute.amazonaws.com:8080/

sh030348/sh030348

Pipeline Syntax:

https://www.jenkins.io/doc/book/pipeline/syntax/

https://www.jenkins.io/doc/book/pipeline/jenkinsfile/

https://www.jenkins.io/doc/pipeline/steps/workflow-basic-steps/




sample:
https://github.com/jenkinsci/pipeline-examples/tree/master/declarative-examples/simple-examples


Built in environment variables
Jenkins provides a set of environment variables. You can also define your own. Here is a list of built in environment variables:

BUILD_NUMBER - The current build number. For example "153"
BUILD_ID - The current build id. For example "2018-08-22_23-59-59"
BUILD_DISPLAY_NAME - The name of the current build. For example "#153".
JOB_NAME - Name of the project of this build. For example "foo"
BUILD_TAG - String of "jenkins-${JOB_NAME}-${BUILD_NUMBER}".
EXECUTOR_NUMBER - The unique number that identifies the current executor.
NODE_NAME - Name of the "slave" or "master". For example "linux".
NODE_LABELS - Whitespace-separated list of labels that the node is assigned.
WORKSPACE - Absolute path of the build as a workspace.
JENKINS_HOME - Absolute path on the master node for Jenkins to store data.
JENKINS_URL - URL of Jenkins. For example http://server:port/jenkins/
BUILD_URL - Full URL of this build. For example http://server:port/jenkins/job/foo/15/
JOB_URL - Full URL of this job. For example http://server:port/jenkins/job/foo/
