nifi-workflow-tool : is used to update Nifi processors by Rest Api

To start Nifi workflow control tool:

2 ways to launch jar file with configuration file:


  1. Place jar file and config file in the same folder and launch:

		java -jar nifi-workflow-0.0.1.jar --spring.config.location=file:./application.yml

  2. They are not in the same folder:
  
		java -jar nifi-workflow-0.0.1.jar --spring.config.location="pathToConfigFile" --spring.config.name=application.yml