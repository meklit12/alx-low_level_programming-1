**C - Dynamic libraries**
=======================
# dynamic liberaries
- genrate one object file for each source code
- fPIC flag ensures the code is postion independent. it wouldn't matter where in the meomry
  its loaded
- c ensures each -o is not linked yet

# how to compile
```
gcc *.c -c -fPIC
```