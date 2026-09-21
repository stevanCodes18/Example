 # Esto es un titulo h1
## Esto es un titulo h2
### Esto es un titulo h3
#### Esto es un titulo h4
##### Esto es un titulo h5
 
 **esto es un texto en negrita** 
 *texto en cursiva*

 ```
 sudo apt install open-21-jdk
 ```

 ```bash
 #!/bin/bash
 echo "Hola mundo"
 ```

 ```python
 celcius = float(input('INtroduce una temperatura en grados celcius:'))
 farenheit = (1.8 * celcius) + 32
 print(f'La temperatura en grados Farenheit es: {farenheit}')
 ```

 ```java
 public class Main{
    public static void main(String[]args){
        System.out.println("Hello world");
    }
 }
 ```

 ```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```
Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

Enlaces a la página web del [IES Celia Viñas][1] y a [GitHub][2].

[1]: https://iescelia.org
[2]: https://github.com

![](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)

**listas**

* Item 1
* Item 2
* Item 3
* Item 4
* Item 5

**Listas desordenadas**
* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  *Item 2.2

* Item 3
* Item 4  

**Listas ordenadas anidadas**

1. Item 1
    1.1 Item 1.1
    1.2 Item 1.2
2. Item 2
   2.1 Item 2.1
3. Item 3
4. Item 4



por ejemplo, en este parrafo 
hemos forzado aun salto de linea.

**citar textos**
Este texto no es un cita.
> Este texto daria como resultado una cita



*comentarios*

Parrafo 1.

<!- Este texto es un comentario y no sera renderizado -->

Parrafo 2.
