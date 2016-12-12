# RosJava Messages

## History

Some history for the annals of time and also for future devs who are wondering about
the boundaries defining the choice of message packages that form the conglomeration
that is rosjava messages.

Several approaches were tried/tested, discarded until we have what is here.

**Scan rosdistro to discover all possible message packages**

Experimental packages often appear/disappear and this triggered too much manual intervention to maintain. There is also far too many packages that have code with it too. This is awkward for rosjava to depend on - I prefer message only packages and have encouraged upstream folk to shift their messages to message only packages in certain instances. 

*Used for hydro, but dropped for indigo*

**Minimal set of messages directly used by rosjava/android**

Easiest to maintain, but not so useful for users - they have to then go off and generate many message packages themselves, even if only using some of the more common packages.

*Used for indigo, but dropped shortly afterwards*

**Minimal set and finite set of stable, popular packages**

Relatively easy to maintain and important for maven repo users since they will not want to go and directly build message packages themselves. If I get a request, I usually add to the list to support these users. 

*Used in indigo*