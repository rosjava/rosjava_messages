## RosJava Messages

This package is a generator of rosjava message artifacts for core ros messages.

### Adding Packages

If you would like to add a message dependency to this list, first consider
if it is a worthwhile candidate:

* It is a direct dependency for rosjava/android
* It is a popular and stable dependency that will require little maintenance

Then to actually add the dependency:

* add the message dependency to package.xml
* add the message dependency to CMakeLists.txt
* create a pull request
* update the changelog and bump the version number in package.xml
* tag it with the new version number
* release

### Rereleasing Version Changes

When the underlying message dependency version numbers shift, this will
require a rebuild of this package:

* update the changelog and bump the version number in package.xml
* tag it with the new version number
* release

### More Information

* [RosJava Message Artifacts](http://wiki.ros.org/rosjava/Tutorials/indigo/RosJava Message Artifacts)

