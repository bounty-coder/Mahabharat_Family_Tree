# Mahabharat Family Tree
This Prolog program is the family tree of mahabharat

To run a query, visit https://swish.swi-prolog.org/p/Mahabharat%20Family%20Tree.pl <br><br>


### Prolog Relationship Features<br>
Relationship is one of the main feature mentioned in Prolog. These relationships can be expressed as facts and rules. In Prolog programs, it specifies relationship between objects and properties of the objects.<br><br>

### We can define a brother relationship as follows −<br><br>
Two person are brothers, if,<br>
- [x] They both are male.<br>
- [x] They have the same parent.<br>
    and Prolog Code for this will be-<br>
* brother(X,Y) :- parent(Z,X), parent(Z,Y),male(X), male(Y).


For more Prolog reference, visit https://www.swi-prolog.org/pldoc/doc_for?object=root
