# profiler_automation
Automation of the Teamscale JaCoCo agent in combination with the Teamscale JavaScript profiler

profiler\_automation.py: Configures and starts the Teamscale JaCoCo agent and the Teamscale JavaScript profiler on test execution.
All configuration needed is the jacocoagent.properties file (generated by Teamscale) and profiler.properties. 

profiler.properties: An example properties file.
	project_folder: path to the  projects source code
	java_framework: the Java build tool used (gradle/maven)
	run_command: command line command to run the test suite
	include_params/exclude: include/exclude parameters for the JavaScript instrumenter, this should link to the JavaScript/Typescript source code