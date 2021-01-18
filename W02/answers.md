# 1:
The second \<p> of the second \<fieldset> could be selected by either of these selectors below. Explain why the first would be a better option than the second.

<code>
fieldset[title=fieldset2] > p + p

fieldset:nth-of-type(2) >p + p
</code>

1) 
The first selector can be used in this case because it's far more clear for the programmer what element it is being selected.
The second selector can potentially select an element not intended for the occasion.


# 2:
Explain the difference the space makes with the following two selectors: "span.help" and "span .help". How does it change what will be selected?

2)
The first selector would look for both element and class within the specified element whereas the second selector will attempt to find the class within that element.

