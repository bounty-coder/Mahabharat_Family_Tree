# Mahabharat_Family_Tree
This Prolog program is the family tree of mahabharat

To run a query, visit https://swish.swi-prolog.org/p/Mahabharat%20Family%20Tree.pl 


###Prolog Relationship Features
Relationship is one of the main features mention in Prolog. These relationships can be expressed as facts and rules. In Prolog programs, it specifies relationship between objects and properties of the objects.

######We can define a brother relationship as follows −

Two person are brothers, if,
-[x]They both are male.
-[x]They have the same parent.
and Prolog Code for this will be
-[]brother(X,Y) :- parent(Z,X), parent(Z,Y),male(X), male(Y).
