---
layout: relation
title: 'list'
shortdef: 'list'
udver: '2'
---

The `list` relation is used for chains of comparable items. In lists with more than two items, all items of the list should modify the first one. Informal and web text often contains passages which are meant to be interpreted as lists but are parsed as single sentences. Email signatures often contain these structures, in the form of contact information: the different contact information items are labeled as `list`; the key-value pair relations are labeled as [appos]().

~~~ sdparse
Steve Jones Phone: 555-9814 Email: jones@abc.edf
flat:name(Steve-1, Jones-2)
list(Steve-1, Phone:-3)
list(Steve-1, Email:-5)
appos(Phone:-3, 555-9814-4)
appos(Email:-5, jones@abc.edf-6)
~~~

Another place where `list` has been used is for a sequence of attributes or descriptive terms used as the title line of a review (such as product or restaurant reviews, etc.:

~~~ sdparse
Long Lines , Silly Rules , Rude Staff , Ok Food
list(Lines, Rules)
list(Lines, Staff)
list(Lines, Food)
~~~

However, `list` should not be over-used. If a construction can be easily analyzed using the grammatical relations of standard sentences, typically as a coordinated structure, and particularly when there is overt coordination, then it should be analyzed with these more standard relations, even if it is laid out as a list typographically.
<!-- Interlanguage links updated Út zář 29 20:43:20 CEST 2020 -->

For list items, the de facto decision taken in [issues 156](https://github.com/UniversalDependencies/docs/issues/156) is that for enumerated lists, regardless of whether the items are numbered with arabic, roman, or other numerals or are given letters, that we will regard the item contents as the head, and the item enumerator will be a `nummod` of it. Any punctuation will be `punct` dependents of the item enumerator. For itemized lists with bullet, dash or similar markers, the current standard is to regard the marker as a `PUNCT` and to give it the dependency relation `punct` to the head of the item content.
