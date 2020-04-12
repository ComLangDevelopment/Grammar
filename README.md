# Grammar
Formal Definition of the Laser Language Grammar in ABNF, with some modifications

ABNF is defined by [[RFC 5234]](https://tools.ietf.org/html/rfc5234).

A Formal definition of the ABNF Syntax is defined in [abnf](latest/abnf.abnf)


## Modifications to the ABNF Syntax

Any rule may have a single trailing "-" rule, which means that the rule DOES NOT match the following. 
This is the "difference" operator,  and takes presidence over all other ABNF operations. 