# Diferencia entre Git merge y Git merge --no--ff

La gran diferencia que podemos encontrar es que **--no--ff** evita que git merge ejecute un "avance rápido"  si detecta que su *HEAD* actual es un antecesor de la confirmación que está intentando funcionar.
Y utilizando *--no--ff* permite a que se revise el historial claramente ver la sucursal que verificó para trabajar.


---
***He aquí una representación gráfica de dicha diferencia:***

![diferencia](https://i.stack.imgur.com/GGkZc.png "difencias")
