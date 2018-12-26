TypeScript Mocha Global Init Demo
=================================

If we want to do some initialization before all tests, we can use `--file` to include the file as command line argument.

Note: use `--require` can have the same effect.

```
npm install
npm test
```

Prints:

```
### do some global initialization


  hello1
hello1
    ✓ hello1

  hello2
hello2
    ✓ hello2


  2 passing (6ms)
```
