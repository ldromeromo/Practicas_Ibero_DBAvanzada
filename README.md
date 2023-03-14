# Practicas_Ibero_DBAvanzada
Script de DB en Mongo DB

Estructura
```JSON
/** 
* TORNEO 
*/
{
  "nombre": "Name",
  "status": "Ganador/  Perdedor",
  "letras registradas": 5,
  "Trucos": {
    "1": "Truco 1",
    "2": "Truco 2",
     .
     .
     .
  },
  "Trucos Fallidos": {
    "S": "Truco 1",
    "K": "Truco 2",
    "A": "Truco 3",
    "T": "Truco 4",
    "E": "Truco 5"
  }
}
```


```JSON
/** 
* Trucos 
*/
  {
    "Truco 1": "Truco",
    "Registrado": "Name"
  }
}
```


```JSON
/** 
* Participantes  
*/
{
  "nombre": "Name",
  "status": "Ganador/  Perdedor"
}
```
