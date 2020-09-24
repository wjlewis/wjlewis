"is quite a lovely sentence
 when preceded by its own quotation."
is quite a lovely sentence
 when preceded by its own quotation.

```racket
;; test
(define q
  ((lambda (x)
     `((lambda (x) ,x)
       ',x))
   '`((lambda (x) ,x)
      ',x)))
```
