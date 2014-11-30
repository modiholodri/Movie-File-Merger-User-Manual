## Regular Expressions
Regular expressions can be very complicated, but MFM uses just basic regular expressions and it should be possible to figure out how they work by looking at the standard settings.

Regular expressions can be tested on the [Rubular website](http://rubular.com).

An over view of regular expression can be found on [Wikipedia](http://en.wikipedia.org/wiki/Regular_expression) from where also the following excerpt is. You can find it also directly on the Setting tab, where regular expressions are used in MFM.

A regular expression, often called a pattern, is an expression that specifies a set of strings.  To specify such sets of strings, rules are often more concise than lists of a set's members.  For example, the set containing the three strings "Handel", "Händel", and "Haendel" can be specified by the pattern `H(ä|ae?)ndel` (or alternatively, it is said that the pattern matches each of the three strings).  In most formalisms, if there exists at least one regex that matches a particular set then there exist an infinite number of such expressions.  Most formalisms provide the following operations to construct regular expressions.

Boolean "or":  A vertical bar separates alternatives. For example, `gray|grey` can match "gray" or "grey".

Grouping:  Parentheses are used to define the scope and precedence of the operators (among other uses).  For example, `gray|grey` and `gr(a|e)y` are equivalent patterns which both describe the set of "gray" and "grey".

Quantification:  A quantifier after a token (such as a character) or group specifies how often that preceding element is allowed to occur. The most common quantifiers are the question mark `?`, the asterisk `*` (derived from the Kleene star), and the plus sign `+` (Kleene cross).

The question mark `?` indicates there is zero or one of the preceding element. For example, `colou?r` matches both "color" and "colour".

The asterisk `*` indicates there is zero or more of the preceding element. For example, `ab*c` matches "ac", "abc", "abbc", "abbbc", and so on.

The plus sign `+` indicates there is one or more of the preceding element. For example, `ab+c` matches "abc", "abbc", "abbbc", and so on, but not "ac".

These constructions can be combined to form arbitrarily complex expressions, much like one can construct arithmetical expressions from numbers and the operations +, −, ×, and ÷. For example, `H(ae?|ä)ndel` and `H(a|ae|ä)ndel` are both valid patterns which match the same strings as the earlier example, `H(ä|ae?)ndel`.
