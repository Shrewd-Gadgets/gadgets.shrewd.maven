# gadgets.shrewd.maven
Parent Maven project object model (POM) for all Shrewd Gadget Maven projects.

## Installation
Since Shrewd Gadgets does not have it's own remote Maven repository developers will need
to install the parent POM into their local Maven repository manual.

To install locally:
 - Clone this [repository](https://github.com/Shrewd-Gadgets/gadgets.shrewd.maven) onto you local machine.
 - Navigate into the root of the project; this is directory containing the `pom.xml` file.
 - Build and install only this component
 ```bash
 [user@localhost:~/gadgets.shrewd.maven] mvn clean install --non-recursive
 ```
 
 This will add the parent POM, and only the parent POM, to your local Maven repository.
