The Forth Hacker's Guide to Neural Networks
-------------------------------------------

- [Differentiable Programming](#differentiable-programming)

## Differentiable Programming

```
           x approaches a
-------------------------------------
(D f x)(x - a) + (f a) approaches f x
   ^      ^        ^
   M      x    +   b 
```

```
    f : a -> b
    x : a
--------------
D f x : a -> b
```

```
D (f + g) x = (D f x)         + (D g x)
D (f * g) x = (D f x) * (g x) + (D g x) * (f x)
D (f ; g) x = (D f x)         ; (D g (f x))

```
