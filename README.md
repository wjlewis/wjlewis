```
(define (t f)
  (if (halts? f)
      (for ever)
      'done))
      
(define (for how-long?)
  (for how-long?))
```
