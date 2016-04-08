Using XStream to build or parse object from & to XML
## So what is the problem to solve ? ##

If you ever used Java's XStream http://xstream.codehaus.org/
you probably encountered that parsing a XML file with more then a few elements and attributes to those elements may be a hampering task, that comes back to hunt you time & time again.

Why isn't there a simple library that wraps XStream for an even easier configuration ?

Well I guess there are a few out there, but most are too complicated to use and have pretty much specific needs.

So I decided to write one simple class !
One that you just extends and follow a few simple conventions to use properly :)
This class will make the Element + Attribute parsing a much faster & easier process then it generally is.

### Scenario for testing ###

  1. Having an xml file to parse to Java objects.
  1. Using XStream aliases to configure the Java objects
  1. Some of the XML Elements will have attributes (N > = 1)