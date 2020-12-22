# Design-Pattern-Facade
 
Facade defines a higher-level interface that make the subsystem easier to use.
You set the name of an object using:
setFirstNameCharacter method -> sets the FIRST CHARACTER of the name
setSecondNameCharacter method -> sets the SECOND CHARACTER of the name
...
setSeventhNameCharacter method -> sets the SEVENTH CHARACTER of the name

The facade is going to wrap the object(DifficultProduct).
You provide the facade with a simple setName method that you pass the name of the object as a String.
That method breaks the name from the String to an ARRAY OF CHARS, and passes those chars on to the wrapped DifficultObject methods setFirstNameCharacter,setSecondNameCharacter...
