# TestingPythonPro
'''
This function takes two arguments,
data1 and data2, which contain
key-value pairs. All key-value
pairs within data1 are unique.
Similarly, all key-value pairs
within data2 are unique. However,
there may be key-value pairs (k, v1)
in data1 and (k, v2) in data2 with a
common key k. In this case, v1 and
v2 may be the same, or v1 and v2 may
be different.

This function should modify only
data1 and return a (possibly empty)
dictionary as follows:
For every key-value pair (k, v2) in
data2, if no key-value pair with key
k exists in data1, then the pair
(k, v2) should be added to data1.
Otherwise, there is a unique pair
(k, v1) already in data1. If v1 and
v2 are different, the pair (k, v1)
should be removed from data1 and the
key-value pair (k, [v1, v2]) should
be added to the (initially empty)
dictionary to be returned.

In this implementation, data1 is a
dictionary and data2 is a list where
each key-value pair in data2 is also
a list [key, value] of length 2.
'''
