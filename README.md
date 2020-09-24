```racket
(define q
  ((lambda (x)
     `((lambda (x) ,x)
       ',x))
   '`((lambda (x) ,x)
      ',x)))

(equal? q (eval q))
```
