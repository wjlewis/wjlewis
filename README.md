```racket
(define q
  '((lambda (u)
      `((lambda (u) ,u)
        ',u))
    '`((lambda (u) ,u)
       ',u)))

(equal? q (eval q))
```
