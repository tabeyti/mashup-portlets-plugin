Jenkins Mashup Portlets
=======================

Additional portlets for jenkins Dashboards (see https://wiki.jenkins-ci.org/display/JENKINS/Dashboard+View)

- Generic JS Portlet: Allows to run arbitrary JS to create content in the portlet 
  content area (if the user has edit rights for the given Dashboard View). The function ajaxViaJenkins() 
  allows running ajax requests avoiding cross domain issues by routing them through jenkins
- Recent Changes Portlet: Will show the recent SCM changes of a configured project
- SonarQube Issues Portlet: Shows issues for the given projects (projects and severity can be configured)
- Sonar Violations Portlet (Sonar <=3.5): Shows violations for the given projects (projects and severity can be configured)
- Sonar Reviews Portlet (Sonar <=3.5): Shows open sonar reviews

NOTE: The SonarQube portlets will be moved to https://wiki.jenkins-ci.org/display/JENKINS/SonarQube+plugin soon.

See help sections in portlet configuration for more information.