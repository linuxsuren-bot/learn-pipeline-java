This project is aim to provide an easy way to try Jenkins pipeline.

According to different use cases, we provide several Jenkinsfile for you:
s
|File|Requirement|Description|
|---|---|---|
|[Jenkinsfile-parameters.groovy](Jenkinsfile-parameters.groovy)|No particular things are required.|A demo about how to use parameters in Jenkinsfile pipeline.|
|[Jenkinsfile-junit-k8s](Jenkinsfile-junit-k8s)|It requires an agent which has a label `maven`. The agent should be a pod which contains a container named `java`.|Generate junit report.|
|[Jenkinsfile-input](Jenkinsfile-input)|Any types of agent.|Require a user to input something, then the Pipeline will keep going.|
|[Jenkinsfile.jmeter.groovy](Jenkinsfile.jmeter.groovy)|A kubernetes environment|Running a JMeter test in Jenkins|
|[Jenkinsfile-milestone.groovy](Jenkinsfile-milestone.groovy)|None|Abort running build if new one is started|
See also https://jenkins-zh.cn/about/course/#1
