#### Discard Old Build plugin
  * [https://wiki.jenkins-ci.org/display/JENKINS/Discard+Old+Build+plugin](https://wiki.jenkins-ci.org/display/JENKINS/Discard+Old+Build+plugin)
  * ![basic](https://wiki.jenkins-ci.org/download/attachments/65670518/discardOldBuild_conf1.png?version=1&modificationDate=1359279566000&api=v2)
  * ![advanced](https://wiki.jenkins-ci.org/download/attachments/65670518/discardOldBuild_conf2.png?version=1&modificationDate=1359279572000&api=v2)

#### Job notification plugin
  * [https://wiki.jenkins-ci.org/display/JENKINS/Notification+Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Notification+Plugin)
  * ![settings](https://wiki.jenkins-ci.org/download/attachments/52297834/new-endpoints.png?version=1&modificationDate=1403198652000&api=v2)
    * "Format" : notification payload format, JSON or XML.
    * "Protocol": protocol to use for sending notification messages, HTTP, TCP or UDP.
    * "Event": job events that trigger notifications: Job Started, Job Completed, Job Finalized or All Events (the default option). The difference between job being "completed" and "finalized" is as follows: when job is finalized all post-build activities, such as archiving artifacts, were executed as well. This is not the case with job being merely "completed" which usually involves only creation of job's artifacts without post-processing them. If you're unsure of which event to use, you can start with "Job Finalized".
    * "URL": URL to send notifications to. It takes the form of "http://host" for HTTP protocol, and "host:port" for TCP and UDP protocols.
    * "Timeout": Timeout in milliseconds for sending notification request, 30 seconds by default.

#### Sidebar-Link Plugin
  * [https://wiki.jenkins-ci.org/display/JENKINS/Sidebar-Link+Plugin] (https://wiki.jenkins-ci.org/display/JENKINS/Sidebar-Link+Plugin)
  * 
#### multiple-configuration(matrix) project
  * [https://wiki.jenkins-ci.org/display/JENKINS/Building+a+matrix+project](https://wiki.jenkins-ci.org/display/JENKINS/Building+a+matrix+project)
  * [https://www.linkedin.com/pulse/jenkins-multi-configuration-matrix-muhammad-zbeedat](https://www.linkedin.com/pulse/jenkins-multi-configuration-matrix-muhammad-zbeedat)
