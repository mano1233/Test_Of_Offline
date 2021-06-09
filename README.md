# Test_Of_Offline

this repo includes a test project of kafka stream and all its required dependencies to create a jar offline.<br/><br/>
in order to accompish this you will need to run the folowing commands on you finished project with ethernet connection:<br/><br/>
1. mvn assembly:help compiler:help enforcer:help exec:help failsafe:help install:help jar:help resources:help surefire:help (Downloads basic plugins make sure the one you use are included)<br/><br/>
2. mvn dependency:go-offline (Download all Dependencies required)<br/><br/>
3. mvn -o clean install (Creates JAR File)
