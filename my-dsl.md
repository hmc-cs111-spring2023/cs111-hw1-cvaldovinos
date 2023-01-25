# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._

The name of the language is Chef.

# Domain

_Describe the language's domain in five words._

Making Programming look like Recipes

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

When a program in Chef runs, it goes through the cookbok and finds each 
recipe (file) which runs as regular Ruby code.

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

I would say this DSL is mostly domain-specific. While it does have some general 
functionality like loops and variables, it is still too verbose to be able to use 
for more general purposes.

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

This language is implemented as an internal DSL because Chef code is still 
able to be ran as valid Ruby code.

# Host language

_What language(s) was (were) used to implement the DSL?_

Ruby was used to implement Chef.

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

The existence of this language presents programming in a different perspective. 
It still maintains the essence of an order of operations (recipe) and variables 
(ingredients) which allow it to be more readable for someone who may not 
understand programming languages.

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

While Chef is very readable, it has the drawback of being too abstract, 
in order to truly understand it, it must still be mapped onto code in a 
general purpose programming language, meaning that the novelty really 
comes at the expense of being far too difficult to write.