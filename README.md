# Test React

La principal ventaja que nos ofrece react es la creación de componentes responsive. Facilitando mucho el trabajo con APIs y asincronismo.

En Nested usamos componentes react para informar a tiempo real a nuestros hosts sobre sus espacios y para que nuestros guests encuentren los espacios en el search.

Tal y cómo os comentamos esta prueba no es un exámen, no os pedimos resultados excelentes ni que seáis unos expertos en react. Lo único que queremos evaluar es vuestra capacidad de enfrentaros a un problema abierto y la capacidad de aprendizaje. Prefermios que nos comentéis cualquier duda y resolverla juntos que no qué os frustréis haciendola 100% solos.

# La idea

Nested va de oficias, pero para esta prueba vamos a jugar un poco! Imagináros que nuestros hosts son todos seguidores de Space X y queremos que puedan ver inforamción de sus lanzamientos en nuestro dashboard.

Space X nos da una api abierta para poder aceder programaticamente a mucha información de sus vuelos y pruebas, por ejemplo, una llamada al endpoint: 

`https://api.spacexdata.com/v3/launches/54`

Nos devuelve un `json` con mucha información de su lanzamiento 54. !Probadlo en vuestro navegador!

En el momento de preparar esta prueba la API da información de 69 vuelos. `https://api.spacexdata.com/v3/launches/1` hasta `https://api.spacexdata.com/v3/launches/69`

Vamos a usar esta API para darle la información de un vuelo aleatorio a nuestros hosts. Queremos crear un componente como este: 

![Card](https://github.com/Nestednet/test-react-front/blob/master/Screenshot%202018-11-12%20at%2014.05.55.png?raw=true) 

Cada vez que se pulse el botón la información del vuelo cambiará por otro vuelo aleatorio.

# Let´s go!

Para hacerlo no os pedimos que configuréis ningún entorno. Podéis utilizar [stackblitz](https://stackblitz.com/) y compartir el enlace conmigo.

Links interesantes: 
[APIs y REACT](https://reactjs.org/docs/faq-ajax.html)


