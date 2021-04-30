# 2.3 String
### Consisten en secuencias de caracteres dentro de comillas, en python se pueen declarar usando doble comillas o comillas simple.


```python
"Esta es una cadena de caracteres"
```




    'Esta es una cadena de caracteres'




```python
name = "Victor"

degree = "Computer Science"

print(name)
print(degree)
```

    Victor
    Computer Science



```python
type(name)
```




    str




```python
name + ' ' + degree
```




    'Victor Computer Science'



### print()
#### Esta funcion nos permite mostrar por pantalla el valor de una variable o algun texto con tabulaciones y saltos de linea


```python
print("Una cadena separada \t por tabulacion")
```

    Una cadena separada 	 por tabulacion



```python
print("Cadena separada \npor salto de linea")
```

    Cadena separada 
    por salto de linea


#### Para que la funcion print nos permita mostrar una cadena sin procesar debemos indicarle que la cadena es tipo crudo, agregando la letra r antes de abrir las comillas


```python
print("c:\nombre\nombre_2")
```

    c:
    ombre
    ombre_2



```python
print(r"c:\nombre\nombre_2")
```

    c:\nombre\nombre_2


#### Tambien podemos indicar que queremos presentar nuestro string en varias lineas de la siguiente forma:


```python
print("""Linea 1 es esta
aqui tenemos la linea 2
y aqui la linea 3...
y asi....
sucesivamente...
Por la eternidad....
""")
```

    Linea 1 es esta
    aqui tenemos la linea 2
    y aqui la linea 3...
    y asi....
    sucesivamente...
    Por la eternidad....
    



```python

```
