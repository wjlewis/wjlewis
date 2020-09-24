```
(define (T f)
  (if (halts? f)
      (loop)
      'done))

(define (loop)
  (loop))
```
