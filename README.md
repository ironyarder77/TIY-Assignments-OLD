# TIY-Assingments
Homework Assignments
WebAPI Terms

LINKS
https://developer.mozilla.org/en-US/docs/Web/API/Window/document
http://stackoverflow.com/questions/15763358/difference-between-htmlcollection-nodelists-and-arrays-of-objects
Document Object Model all web pages have document object. this is the location on your screen where all the content. a document object can be obtained from a number of different api's. all document objects instantiate the document interface as well as the node.

WindowDocument example found: Returns a reference to the document contained in the window.
all web pages have what is called a (document object).this is the location on your screen where all the content is displayed. basically, it is the main body of the screen.
an api, in my mind, is a sort of interface. it acts as a facilitator in a way an illustration of this would be when new html elements are added, the Dom will return, "new content added.”  However, technically speaking there is another use of this word when attempting to define "the DOM”. it enables flow within the html, javascript constructed mod. all document objects instantiate the document interface as well as the node and Event Target or where error occurred.

The NodeOwner Property-The document that a given node or element belongs to can be retrieved using the node's ownerDocument property. Depending on the kind of the document (e.g. HTML or XML), different APIs may be available on the document object.
I'm having a little difficulty visualizing this and then I realized maybe I should not be trying to visualize this. Letting certain context remain abstract, surface, and superficial at this time might be crucial to truly understanding what is happening during any operation. My journal reflects this as well to a certain extent.

HTMLElement -Element interface represents an object of a Document. This interface describes methods and properties common to all kinds of elements. Specific behaviors are described in interfaces which inherit from Element but add additional functionality. For example, the HTMLElement interface is the base interface for HTML elements.

HTMLCollection-EDITED with Correct Definition. This is a collection of HTML and XTML documents . useful in retrieval.

Nodelist- is a node, but isn't an HTML element." So, basically that means that even though the actual text in an html paragraph tag is a node but not an element" Again, i think this has to do with sorting various sectors of the code to fix or otherwise alter.
Nodelist a Nodelist is an array of nodes basically. Example found: var x = document.getElementsByTagName("p"); The nodes can be accessed by an index number. To access the second
node you can write:
y = x[1];

