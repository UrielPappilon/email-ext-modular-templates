Modular templates for email-ext Jenkins plugin
-------------------------
###Based on:
 [email-ext](https://github.com/jenkinsci/email-ext-plugin) templates examples

###Usage
To use those templates:

1) Put templates into $JENKINS_HOME/email-templates/ folder

2) Put into email notification content
```
${JELLY_SCRIPT,template="style"}
${JELLY_SCRIPT,template="general"}
```