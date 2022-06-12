<h1 align="center"> TALLER API GOLANG POKEMON 1 </h1>
<p align="center">
  <img src="https://grapee.jp/en/wp-content/uploads/Untitled-220.jpg" width="350" title="hover text">

</p>


<div  align="justify">
<p   align="left">
  
  La idea es probar conceptos de api rest con lenguaje de programación golang, ocupando una API publica llamada "PokeApi" la cual podemos encontrar en el siguiente link, https://pokeapi.co/ , en ella tendremos acceso a la información de muchos pokemon, podemos encontrar algunas pequeñas instrucciones de uso escritas en ella, será vital aprender sus llamados para el cumplimiento optimo de este taller.
 
</p>
  
 <h2> Planteamiento del problema </h2>
  
  El area de desarrollo de nintendo encontró problemas en el filtrado de tipos de pokemon, entre otras cosas el sistema estaba indicando por ejemplo que Pikachu era tipo FUEGO, lo que puso en marcha un cambio en la API principal de filtrados de tipos Pokemon.
  
  <h2> Requerimientos </h2>
  
  <ul>
    <li>
        Construir una API en Golang que exponga un Endpoint de tipo GET llamado "localhost:8080/api/v1/pokemon/filter" expuesto en el puerto 8080.
    </li>
     <li>
        Este endpoint debe recibir por un Query Params el TIPO de pokemon en inglés (ghost,normal,fire)
    </li>
    <li>
        El endpoint debe devolver un JSON que contenga la cantidad total de pokemones encontrados de ese TIPO, ademas de un ARRAY indicando su nombre,peso,altura, y habilidades.
    </li>
    <li>
        Si se inserta un TIPO que no existe, la API debe devolver un 404 not Found
    </li>
       <li>
        Subir codigo a repositorio GITHUB publico indicando instrucciones de compilado en un Readme.md para poder clonarlo y correrlo en ambiente local
    </li>
  </ul>  



</div>

<div>
    <h2> Tips </h2>
      <ul>
    <li>
        Se recomienda utilizar herramientas para el testeo de APIS ocupadas en el mercado como POSTMAN
    </li>
      <li>    
       Ademas se recomienda ocupar algun software como  https://jsonformatter.curiousconcept.com/ para ayudarte con el manejo de JSON de gran tamaño
   </li>
  </ul>  

   <h2 align="center"> Quedamos a la espera de tu repositorio ! </h2>
<p align="center">
  
  
  <img src="https://pbs.twimg.com/media/DexLZATWkAAfvKX?format=jpg&name=small" width="350" title="hover text">

</p>
  
 

</div>

