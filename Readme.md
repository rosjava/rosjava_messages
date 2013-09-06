h2. RosJava Messages

h3. Message Generator

All the code for the message generation is bundled in here. It relies on no
other rosjava code, and likewise, no other rosjava code relies on it.

h3. Message Artifacts

*Your regular rosjava message project does not need this complexity!*

The gradle magic in settings.gradle is responsible for kickstarting the following
very useful things for a big release of message packages:

* 1-1 correspondence between msg pkg and artifact for a large list of artifacts
* Automagically discovers the msg pkg version adn applies it to the artifact

It manages the correspondence by dynamically creating subprojects from a template.
This saves a very large amount of tedious and repetitive gradle management.

The version information is discovered in the source code generation step and
passed along to the maven artifact creation tasks.
