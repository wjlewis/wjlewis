Lovely.

```racket
;; "is quite a lovely sentence
;;  when preceded by its own quotation."
;; is quite a lovely sentence
;;  when preceded by its own quotation.
(define q
  ((lambda (x)
     `((lambda (x) ,x)
       ',x))
   '`((lambda (x) ,x)
      ',x)))
```
