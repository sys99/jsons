# casos.json


objgen.con

## cliente 
```
id = CLC
nombre = Cliente C
contratos[0]
  id = CLC-CONT01
  nombre = Contrato 1
  tipo
    id = CONT-TIPB
    nombre = Tipo B
   actividades[0]
     id = ACT-B1
     nombre = Actividad B1
   actividades[1]
     id = ACT-B2
     nombre = Actividad B2
   actividades[2]
     id = ACT-B3
     nombre = Actividad B3
  productos[0]
    id = PRODB1
    nombre = Producto B1
  productos[1]
    id = PRODB2
    nombre = Producto B2
  productos[2]
    id = PRODB3
    nombre = Producto B3
contratos[1]
  id = CLC-CONT02
  nombre = Contrato 2
  tipo
    id = CONT-TIPC
    nombre = Tipo C
   actividades[0]
     id = ACT-C1
     nombre = Actividad C1
   actividades[1]
     id = ACT-C2
     nombre = Actividad C2
   actividades[2]
     id = ACT-C3
     nombre = Actividad C3
  productos[0]
    id = PRODC1
    nombre = Producto C1
  productos[1]
    id = PRODC2
    nombre = Producto C2
  productos[2]
    id = PRODC3
    nombre = Producto C3
solicitantes[0]
  id = CLC-SA
  nombre = Solicitante A
solicitantes[1]
  id = CLC-SB
  nombre = Solicitante B
solicitantes[2]
  id = CLC-SC
  nombre = Solicitante C
```
## Lista de casos resumida
```casos[0]
  id = CASO01
  nombre = Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor.
  fecha
    inicio = 1496088857
  estado
    id = 1
    nombre = pendiente
  severidad
    id = S04
    nombre = Severidad 4
  cliente
    id = CLB
    nombre = Cliente B
  solicitante
    id = CLB-SB
    nombre = Solicitante B
  Producto
    id = PRODA2
    nombre = Producto A2
casos[1]
  id = CASO03
  nombre = Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor.
  fecha
    inicio = 1496088857
  estado
    id = 2
    nombre = trabajando
  severidad
    id = S01
    nombre = Severidad 1
  cliente
    id = CLC
    nombre = Cliente C
  solicitante
    id = CLC-SA
    nombre = Solicitante A
  Producto
    id = PRODC3
    nombre = Producto C3
casos[2]
  id = CASO06
  nombre = Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor.
  fecha
    inicio = 1496088857
  estado
    id = 1
    nombre = pendiente
  severidad
    id = S02
    nombre = Severidad 2
  cliente
    id = CLA
    nombre = Cliente A
  solicitante
    id = CLA-SC
    nombre = Solicitante C
  Producto
    id = PRODB3
    nombre = Producto B3
casos[3]
  id = CASO10
  nombre = Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor.
  fecha
    inicio = 1496088857
  estado
    id = 2
    nombre = trabajando
  severidad
    id = S03
    nombre = Severidad 3
  cliente
    id = CLB
    nombre = Cliente B
  solicitante
    id = CLB-SB
    nombre = Solicitante B
  Producto
    id = PRODA1
    nombre = Producto A1
casos[4]
  id = CASO12
  nombre = Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor.
  fecha
    inicio = 1496088857
  estado
    id = 1
    nombre = pendiente
  severidad
    id = S01
    nombre = Severidad 1
  cliente
    id = CLC
    nombre = Cliente C
  solicitante
    id = CLC-SC
    nombre = Solicitante C
  Producto
    id = PRODB1
    nombre = Producto B1
```
## Tipos de contrato

```
tiposContrato[0]
  id = CONT-TIPA
  nombre = Contrato tipo A
  actividades[0]
    id = ACT-A1
    nombre = Actividad A1
  actividades[1]
    id = ACT-A2
    nombre = Actividad A2
  actividades[2]
    id = ACT-A3
    nombre = Actividad A3
tiposContrato[1]
  id = CONT-TIPB
  nombre = Contrato tipo B
  actividades[0]
    id = ACT-B1
    nombre = Actividad B1
  actividades[1]
    id = ACT-B2
    nombre = Actividad B2
  actividades[2]
    id = ACT-B3
    nombre = Actividad B3
tiposContrato[2]
  id = CONT-TIPC
  nombre = Contrato tipo C
  actividades[0]
    id = ACT-C1
    nombre = Actividad C1
  actividades[1]
    id = ACT-C2
    nombre = Actividad C2
  actividades[2]
    id = ACT-C3
    nombre = Actividad C3
```
