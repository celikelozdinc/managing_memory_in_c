

## Common Memory Pitfalls
+ Dangling pointers
+ Double `free`s
+ Forgetting the use of `sizeof`


##  Function Pointers
Makes it possible to call functions `dynamically` at runtime, makes C programms flexible

```bash
gcc function_pointers.c -o function_pointers ; ./function_pointers spanish ; rm -rf ./function_pointers
```

```bash
gcc function_pointers.c -o function_pointers ; ./function_pointers english ; rm -rf ./function_pointers
```