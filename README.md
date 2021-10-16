# self-tm
In the spirit of the recursion theorem... constructing Turing-machine SELF in Python.
The program is really quite short:
```Python
def self(self_): print(self_); print("s = " + repr(self_)); print("self(s)")
s = 'def self(self_): print(self_); print("s = " + repr(self_)); print("self(s)")'
self(s)
```