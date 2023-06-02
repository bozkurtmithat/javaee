# The Project Aim
This project is for experiments and exercises on java ee platform using open liberty. Especially it tests multi-module projects. This project uses maven for build-tool and Multi-module project structure is as following

```javascript
EAR
--> META-INF
--+--> MANIFEST.MF 
--+--> application.xml
--> lib/
--+--> XYZ-util.jar
--> XYZ-EJB.jar
--> XYZ-Web.war
```
Maven packaging generates ear and war at "skinny war" enabled mode.

