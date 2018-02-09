# Simple is a high performance XML serialization and configuration framework for Java

Its goal is to provide an XML framework that enables rapid development of XML configuration and communication systems. This framework aids the development of XML systems with minimal effort and reduced errors. It offers full object serialization and deserialization, maintaining each reference encountered. In essence it is similar to C# XML serialization for the Java platform, but offers additional features for interception and manipulation.

_Author:_ *Niall Gallagher*

:exclamation: Read the fine print, below.

## Simple framework with powerful capabilities
The framework used to provide XML serialization is simple to use and revolves around several annotations an a single persister object used to read and write objects to and from XML.

## Can handle cycles in the object graph
The persistence engine can handle cycles in the object graph, which enables complex objects with recursive references to be serialized. This ensures that the deserialization process can recover all object references.

## It requires absolutely no configuration
Unlike many of the XML frameworks for Java there are no mappings or configuration required to serialize objects regardless of its complexity. The XML schema is represented using field annotations.

## Extremely rapid development with XML
Developing XML configuration and communication systems can be done much quicker than through the use of XML frameworks such as DOM, SAX, and even other frameworks such as Digester and XStream.

## Converts to and from human editable XML
A primary goal for the framework is that the XML data used to deserialize a serialize objects is human readable. All XML elements and attributes take a simple structure that can be easily created with a text editor.

## Contains an XML templating system
As part of the deserialization process template markers within the XML elements and attributes can be replaced with variables. This allows the system to be easily adapted for use as a configuration system with dynamic value substitution.

:exclamation:

<span style="font-size: 10px;">
This repo was initialized from the source download, `simple-xml-2.7.1.zip` from the site https://sourceforge.net/projects/simple/</span>

<span style="font-size: 10px;">The maintainer's email address is dead and there's been no activity since 2014.  Consider also using JAXB2: https://github.com/javaee/jaxb-v2
</span>
