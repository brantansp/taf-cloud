
### To download the Selenium-server jar file
>curl https://github.com/SeleniumHQ/selenium/releases/download/selenium-4.14.0/selenium-server-4.14.1.jar --output selenium-server.jar


### To start the hub we need java jdk 11 as minimum requirement

>java -jar selenium-server.jar hub


### To start a node in the same machine as hub

>java -jar selenium-server.jar node

>java -jar selenium-server.jar node --port 5555

>java -jar selenium-server.jar node --hub http://<hub-ip>:4444
