# ${project_name}

${project_description}

## License

This project is licensed under the [${license_name}](${license_url}).

## Contributing

This project is auto-generated by [Schema Salad](https://github.com/common-workflow-language/schema_salad)
and likely should not be modified directly. Instead consider filing an issue or opening
a pull request against the Schema Salad repository.

## Requirements

This Java library requires Java 8+. Building and testing this project requires
[Apache Maven](https://maven.apache.org/) (``mvn``).

## Usage

Compile the project, test it, and build a jar

    $ mvn install
    $ ls target/  # jar file in here

Building a standalone jar with all dependencies included and use it to validate a document

    $ mvn assembly:single
    $ java -jar target/<project_name>-0.0.1-SNAPSHOT-jar-with-dependencies.jar ../path/to/document.yml

Building and viewing JavaDocs

    $ mvn javadoc:javadoc
    $ open target/site/apidocs/index.html