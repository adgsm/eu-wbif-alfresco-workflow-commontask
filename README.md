# Alfresco Activiti User Task extension AMP, Activiti User Task extension model

Activiti User Task extension model that provides out-of-the-box task approval/rejection functionality
![](https://raw.githubusercontent.com/adgsm/eu-wbif-alfresco-workflow-commontask/gh-pages/common-user-task.png)

### Usage

#### Create AMP
```
mvn clean install
```
#### Install AMP
```
/opt/alfresco/bin/apply_amps.sh
```
or
```
java -jar /opt/alfresco/bin/alfresco-mmt.jar install eu-wbif-alfresco-workflow-commontask /opt/alfresco/tomcat/webapps/alfresco.war
```

### License
Licensed under the MIT license.
http://www.opensource.org/licenses/mit-license.php
