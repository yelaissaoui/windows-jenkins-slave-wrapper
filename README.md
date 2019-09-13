# windows-jenkins-slave-wrapper
Manual configuration of a windows service wrapper for Jenkins slave

* Download the latest version of winsw on : https://github.com/kohsuke/winsw/releases
* Rename the executable to jenkins-slave.exe
* Modify the content of jenkins-slave.xml to meet your environment ( Copy the command java -jar agent.jar -jnplURL xxx from your master instance ) 
* Put the three files in the same directory and run : ./jenkins-slave.exe install
* You can start the service using ./jenkins-slave.exe start
* Check that the service is running automatically on Windows Service Manager
