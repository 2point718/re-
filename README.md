# re*#* [![Build Status](https://circleci.com/gh/2point718/rehash.svg?style=svg)](https://circleci.com/gh/2point718/rehash)
JVM language

# Goals (draft)

* [no null](http://stackoverflow.com/questions/28106234/are-there-languages-without-null) (optionals can be determined the way SDO uses isSet on primitives) - no regard for memory!?!
* beans with properties (struct person { str firstName; str lastName;}) [no getters/setters](http://www.yegor256.com/2014/09/16/getters-and-setters-are-evil.html)
* merge friendly (not as whitespace significant as python but newlines matter)
* built-in [logging](https://golang.org/pkg/log/)
* built-in unit testing support
* no string literals to force NLS and constants (extreme?)
* data types num, str, bool, list, map
* +,-, [] operators can be applied on list and map
* control structures limited to if and for
* embed Java directly in [special blocks](https://msdn.microsoft.com/en-us/library/ms973872.aspx)
* for loop label is implicit counter
