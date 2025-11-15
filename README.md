# stack-notation

stack notation highlighter

Web based editor component that takes forth source code and renders
stack notation in the gutter between the source code lines. It knows about
the individual stack operations and can render the stack state before and
after each line of code.

```
   a |
     | drop
     |
```

```
   a |
     | dup
 a a |
```

```
   a |
     | dup
 a a |
     | drop
   a |
```

```
 a b |
     | +
   c |
```

```
   a b |
       | over
 a b a |
```

```
   a b |
       | swap
   b a |
```

```
   a b |
       | over +
   a c |
```
