**This project is not being actively developed or maintained.**

# re*#*
JVM language (source to source translation)

# Goals (draft)

* [no null](http://stackoverflow.com/questions/28106234/are-there-languages-without-null)
* use a companion attribute to store null state if needed - eg: a null column in database mapped back to a struct attribute
* embed Java directly in [special blocks](https://msdn.microsoft.com/en-us/library/ms973872.aspx) 
* two data types: str (default empty string), num (default 0 backed by BigDecimal)
* container built in types with specific datatype/struct in them: list [], map {}, set () 
* procedural language (proc mutable, func immutable)
* struct with only attributes for object type data structure
* control stuctures - if(boolean condition), while(boolean condition), while(item,itemindex in iterable)
