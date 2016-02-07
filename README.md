# re*#* [![Build Status](https://circleci.com/gh/2point718/rehash.svg?style=svg)](https://circleci.com/gh/2point718/rehash)
JVM language

# Goals (draft)

* [no null](http://stackoverflow.com/questions/28106234/are-there-languages-without-null) ([optionals](http://www.scala-lang.org/api/current/index.html#scala.Option) need a companion bool property) - a little greedy on [memory](http://www.statisticbrain.com/average-historic-price-of-ram/)!!!
* beans with properties (struct person { str firstName; str lastName;}) [no getters/setters](http://www.yegor256.com/2014/09/16/getters-and-setters-are-evil.html)
* source control/merge friendly (not as whitespace significant as [python](https://unspecified.wordpress.com/2011/10/18/why-pythons-whitespace-rule-is-right/) but newlines matter)
* built-in [logging](https://golang.org/pkg/log/)
* no literals outside of enum to force NLS/i18n and externalized constants (extreme?)
* data types num, str, bool, list, map
* +,-, [] operators can be applied on list and map
* control structures limited to 'if' and 'for'
* embed Java directly in [special blocks](https://msdn.microsoft.com/en-us/library/ms973872.aspx) 
* loop label acts as implicit counter
