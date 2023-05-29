# The Project Aim
This project is for experiments and exercises on java ee platform using open liberty. Especially it test the working of multi-module projects. This project uses mavan for build tool and Multi module projects structure as following

EAR
+-- META-INF
  +--- MANIFEST.MF
  +--- application.xml
+-- lib/
  +--- XYZ-util.jar
+-- XYZ-EJB.jar
+-- XYZ-Web.war


Maven packaging generates ear and war at "skinny war" enabled mode.

