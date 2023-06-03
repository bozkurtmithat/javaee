# The Project Aim
This project is for experiments and exercises on java ee platform using open liberty. Especially it tests multi-module projects. This project uses maven for build-tool and Multi-module project structure is as following

```javascript
my-parent
--> myear
--> myejb 
--> myutil
--> myweb
--> myutil.jar
--> pom.xml
```
If you run "maven install" under the "my-parent" folder It creates EAR file as following structure 

```javascript
myear
--> META-INF/
--+--> MANIFEST.MF 
--+--> application.xml
--> lib/
--+--> myutil.jar
--> myejb.jar
--> myweb.war
```
Maven packaging generates ear and war at "skinny war" enabled mode.

