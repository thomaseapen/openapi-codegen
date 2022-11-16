# openapi-codegen


Keep your swagger file and run the following command to create the complete codebase to invoke the service:

java -jar openapi-generator-cli-4.3.1.jar generate -g spring -i petstore.yaml -c config.json -o spring-boot-codegenerator

petstore.yaml - OpenAPi file for code generation
config.json - package structure for code generation
