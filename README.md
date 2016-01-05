# re*#*
JVM language (source to source)

# Goals

* no null (optionals handled similar to the way SDO uses isSet on primitives)
* beans with properties (struct) 
* built-in logging
* unit testing support
* no string literals. string literals need to be externalized in enum
* data types num, str, bool, list, map
* +,-, [] operators can be applied on list and map
* control structures limited to if and for
* embed Java directly in special blocks
* for loop label is implicit counter
