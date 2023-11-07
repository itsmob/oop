There are 2 types of methodologies to use:

-OMT: object modeling techniques (since 1991)

![OMT](/2modeling_diagrams/OMT_Example.png)

-UML: unified modeling language (since 1997), is a standard language for modeling of object oriented systems
es un lenguaje estándar de modelado de sistemas orientados a objetos. This means we have a graphic way of represents a IRL situation or abstract situation.

In order to make representations we can use the following elements:

# - Clases

![clases](/2modeling_diagrams/clases.png)

The attributes or properties are placed on the middle, and going down we will find the operations of the class. You will notice the first character starts with a symbol, this will denote the visibility of the attribute or method, this is a term related to Encapsutalion.

This are the visibility levels:

- -private
- +public
- #protected
- ~default

# Arrows

a way to represent relationships that the element will have with other is by drawing arrows:

- Association

![association](/2modeling_diagrams/association.png)

As its name says, you will notice that every time this type of arrow is referenced it will mean that that element contains the other in its definition. The arrow will point to the dependency.

![example](/2modeling_diagrams/b%20depends%20on%20a.png)

With this we see that class A is associated with and depends on ClassB

- Inheritance

![inherit](/2modeling_diagrams/inherit.png)

Whenever we see this type of arrow, inheritance is being expressed.
The direction of the arrow will go from the child to the parent.

![b inherit from a](/2modeling_diagrams/a%20inherit%20b.png)

In this case class B inherits from class A

- Aggregation

![aggregation](/2modeling_diagrams/aggregation.png)

This is similar to the association in which one element will depend on the other, but in this case it will be: One element will depend on many others. Here we take as reference the multiplicity of the element. What you would commonly know in Databases as one-to-many relationships

![a aggregation b](/2modeling_diagrams/a%20aggregation%20b.png)

With this we say that ClassA contains several elements of ClassB. The latter are commonly represented with lists or collections of data.

- Composition

![composition](/2modeling_diagrams/composition.png)

This is similar to the previous one, only that their relationship is totally interpenetrated in such a way that conceptually one of these classes could not live if the other did not exist.

![b composition a](/2modeling_diagrams/b%20composition%20a.png)

ClassB is composed of ClassA

![example](/2modeling_diagrams/example.png)
