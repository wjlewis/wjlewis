```racket
'((lambda (u)
    `((lambda (u) ,u)
      ',u))
  '`((lambda (u) ,u)
     ',u))
```
