# Loops

## for

```
         1         2      3
for (int i = 1; i <= 20; i++) {
   // do work here
}
```
1. declare `i` as `int` and set to initial value
2. set end condition
3. set incrementer

### Things to remember

* NEVER have a `;` after your `if ()` statement!
* ALWAYS put the "work" of the loop inside `{}`
* NEVER increment the loop couter `i` outside of the `for` loop declaration

## while

```
int i = 0;             // declare and set the intial value of i
while (i <= 30) {      // declare while and end condition of the loop
   // do work here
   i++;                // increment the loop counter
}
```

## do while

```
int i =0;              // declare and set the intial value of i, the loop counter
do {
   // do work here
   i++;                // increment the loop counter
} while (i <= 30)      // declare end condition of the loop
```
