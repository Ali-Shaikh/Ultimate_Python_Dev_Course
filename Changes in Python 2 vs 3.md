**https://docs.python.org/3.0/whatsnew/3.0.html**

**Print Is A Function**

```
The print statement has been replaced with a print() function, with keyword arguments to replace
most of the special syntax of the old print statement (PEP 3105). Examples:

Old: print "The answer is", 2*2
New: print("The answer is", 2*2)

Old: print x,           # Trailing comma suppresses newline
New: print(x, end=" ")  # Appends a space instead of a newline

Old: print              # Prints a newline
New: print()            # You must call the function!

Old: print >>sys.stderr, "fatal error"
New: print("fatal error", file=sys.stderr)

Old: print (x, y)       # prints repr((x, y))
New: print((x, y))      # Not the same as print(x, y)!
```

**raw_input() was renamed to input()**



