<h1>Pointer cheat sheet, because I am an idiot and I keep forgetting things</h1>

```c
int* p;  // pointer uninitialized
int c;   // variable uninitialized

c = 10;  // initialize variable

// BAD
*p = 10; // incorrect because pointer is uninitialized, dereference it by (*p) will give trouble
*p = c;  // incorrect, same as above

// OK
p = &c;  // ok, this gives p an address, then assign the value
*p = c;  // assign value to pointer

// or else
p = (int*)malloc(sizeof(int));
*p = c;
```

