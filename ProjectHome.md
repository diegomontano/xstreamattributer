XStream is a great XML library highly used in many places,
so as my work place.
One thing that puzzles me, why nobody wrote a helper library for XStream, preventing us from rewriting code and implementing hard to read inteffaces (Like the Converter.class which performs the marshalling of the XML file)

So I decided to make my like easier, when ever I have an element with an attribute or attributes, by having a generic class to implement and that the element & attribute parsing wiil be handled fast and easliy.