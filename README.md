# Bienvenidos al Curso de MarkDown 
## Puedes ver el curso aqui [video](https://youtu.be/amG9h2xspbY 'Curso Completo de MarkDown')

### Nota!!!
El curso se dividio por secciones, por lo que este tambien estará divido de esa manera, espero te guste el contenido de mi canal y puedas suscribirte :smile::smile: 

### Links
| [Generar Tablas](https://www.tablesgenerator.com/markdown_tables# ) | 
[Emojies](https://gist.github.com/rxaviers/7360908) |
[Badges Estaticos](https://github.com/Ileriayo/markdown-badges) |
[Badges Dinamicos](https://shields.io/badges/static-badge) |

# Secciones
---


---
> ## Seccion 1 : _Titulos y Textos_
---

<!-- Este es un comentario  -->


<h1>Titulo h1</h1>
<h2>Titulo h2</h2>
<h3>Titulo h3</h3>
<h4>Titulo h4</h4>
<h5>Titulo h5</h5>
<h6>Titulo h5</h6>

# Titulo h1
## Titulo h2
### Titulo h3
#### Titulo h4
##### Titulo h5
###### Titulo h6


Hola como estas?

<p>Hola como estas?</p>

<span>Soy un Span</span>

**Soy un texto en negrita**

Hola soy un texto en **Negrita** y este tambien **negrita**

_Soy un texto en cursiva_

**_Soy un texto en cursiva y negrita_**

<ins>Soy un texto subrayado</ins>

<center>Soy texto en el centro</center>

<center><ins>Soy un texto subrayado en el centro</ins></center>


**<center><ins>Soy un texto subrayado en el centro</ins></center>**

<p style="color:red">Soy un texto a color</p>

> Un desarrollador de software no implementa código limpio con un látigo atrás --Rafael Gómez

<hr>

---
---



---
> ## Seccion 2 : _Códigos de Programación_
---
<h1>Como agregar códigos de programación</h1>

---

## Código en JavaScritp

```js
function mostrarHolaMundo() {
	for (let i = 0; i < 5; i++) {
		console.log('Hello, world!');
	}
}
```
## Código en Python
``` py

def myFunction(num):
	print("El numero ingresado es: ",num)
```

## Código en Java
``` java

public class Main {
    public static void main(String[] args) {
        int numero1 = 5;
        int numero2 = 8;
        System.out.println(compararNumeros(numero1, numero2));
    }

    public static String compararNumeros(int num1, int num2) {
        if (num1 > num2) {
            return "El número mayor es: " + num1;
        } else if (num2 > num1) {
            return "El número mayor es: " + num2;
        } else {
            return "Los números son iguales";
        }
    }
}

```

---
> ## Seccion 3 : _Listas_
---

# Listas


### Listas Desordenadas

- Privacidad
- Seguridad
* Hola
* Soy un item

* Item
    * Subitem 1
        * Sub item
    * Subitem 2


Con HTML
---

<ul>
    <li>Soy un item</li>
        <ul>
        <li>Soy un subitem</li>
        <li>Soy otro subitem</li>
        </ul>
    <li>Soy otro Item</li>
    <li>Soy un tercer item</li>
</ul>

### Listas Ordenadas

1. Soy un item
    1. Soy un subitems
        1. Soy un subitem
        2. Otro subitem

Con HTML
---

<ol>
    <li>Soy un item</li>
        <ol>
        <li>Soy un subitem</li>
        <li>Soy otro subitem</li>
        </ol>
    <li>Soy otro Item</li>
    <li>Soy un tercer item</li>
</ol>


### Listas Combinadas

1. Soy un segundo item
    1. Hola souy yo
    * como estas?
        * Dime que estas bien


Con HTML
---

<ul>
    <li>Soy un item</li>
        <ol>
        <li>Soy un subitem</li>
        <li>Soy otro subitem</li>
        </ol>
    <li>Soy otro Item</li>
    <li>Soy un tercer item</li>
</ul>


---
> ## Seccion 4 : _Links_
---

## Links

---

Visita mi canal de youtube: [Canal](https://www.youtube.com/channel/UC4r9fia857HbFKswu9YqaCg 'MF Dev')


**Visita mi canal de youtube:** _[Canal](https://www.youtube.com/channel/UC4r9fia857HbFKswu9YqaCg 'MF Dev')_

Correo: <miguel@gmail.com>

Esta es una referencia a mi portfolio [1]

[1]: https://portfolio-miguel-fernandez-v2.vercel.app/

---
> ## Seccion 5 : _Imágenes_
---

## Imagenes

![Programando](https://media4.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif 'Programando con MF Dev')

<a href="ttps://www.youtube.com/channel/UC4r9fia857HbFKswu9YqaCg" target="_blank">
    <img src="https://www.roadshow.com.ar/wp-content/uploads/programar.jpg" width="80%" height="auto">
</a>


---
> ## Seccion 6 : _Videos_
---

## Videos


[![video](https://img.youtube.com/vi/XWC5d1g_y1Y/maxresdefault.jpg)](https://www.youtube.com/watch?v=XWC5d1g_y1Y&list=PLl59slIUKc8WljEv2ByY_g4-13akO6969)



[![video](https://res.cloudinary.com/dgp4xwknu/image/upload/v1709583220/Fotografias%20para%20recomendaciones/intro_cyelmu.png)](https://www.youtube.com/watch?v=XWC5d1g_y1Y&list=PLl59slIUKc8WljEv2ByY_g4-13akO6969)


---
> ## Seccion 7 : _Badges y Emojies_
---

## Emojies

:smile:  :computer:  :cat:  :dog: :ocean: :wolf:



## Badges

Usualmente uso el buscador

![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white) 

![Mega.nz](https://img.shields.io/badge/Mega-%23D90007.svg?style=for-the-badge&logo=Mega&logoColor=white)


![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)

![Opera](https://img.shields.io/badge/Opera-FF1B2D?style=for-the-badge&logo=Opera&logoColor=white)

![OneDrive](https://img.shields.io/badge/OneDrive-0078D4.svg?style=for-the-badge&logo=microsoftonedrive&logoColor=white)

![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

## Badges Dinamicos

---
> Nota: Recuerda cambiar el `UserName` por tu nombre de usuario en GitHub
---

Mis seguidores de GitHub ![github](https://img.shields.io/github/followers/UserName?style=social)

![Profile View Counter](https://komarev.com/ghpvc/?username=UserName)

![GitHub followers](https://img.shields.io/github/followers/UserName)



![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=UserName&show_icons=true)

![Your Repository's Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=UserName&theme=blue-green)


---
> ## Seccion 8 : _Tablas_
---

## Tablas


| Lenguajes | Sabes? |
| ----------|--------|
| Python    |  Si    |
| Java      |  Si    |
| Cobol     |  No    |


| Nombre  | Apellido  |  dni | legajo  |
|---|---|---|---|
| Miguel  |  Fernandez | 123123  |  4244 |
|  Gabriel | Ibañez  | 5474575  | 3534534  |
| Ivan  | Herbandez  |  2342 |  23423 |
|  Hola |  fsdfsd |  4346 |  345345 |
