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
  fecha
    inicio=1496229917
    cierre=1596229917
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
    servidores[0]
      id=CLC-SERV-B1
      nombre=Servidor B1
      tipo=producción
  productos[1]
    id = PRODB2
    nombre = Producto B2
    servidores[0]
      id=CLC-SERV-B2
      nombre=Servidor B2
      tipo=producción
    servidores[1]
      id=CLC-SERV-B2B
      nombre=Servidor B2B
      tipo=pruebas
  productos[2]
    id = PRODB3
    nombre = Producto B3
    servidores[0]
      id=CLC-SERV-A
      nombre=Servidor B3
      tipo=producción
contratos[1]
  id = CLC-CONT02
  nombre = Contrato 2
  tipo
    id = CONT-TIPC
    nombre = Tipo C
  fecha
    inicio=1496229917
    cierre=1596229917
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
    servidores[0]
      id=CLC-SERV-C1
      nombre=Servidor C1
      tipo=producción
  productos[1]
    id = PRODC2
    nombre = Producto C2
    servidores[0]
      id=CLC-SERV-C2
      nombre=Servidor C2
      tipo=producción
  productos[2]
    id = PRODC3
    nombre = Producto C3
    servidores[0]
      id=CLC-SERV-C3
      nombre=Servidor C3
      tipo=producción
proyectos[0]
  id = CLC-PRO01
  nombre = Proyecto 1
  tipo
    id = PROY-TIPB
    nombre = Tipo B
  fecha
    inicio=1496229917
    cierre=1596229917
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
    servidores[0]
      id=CLC-SERV-B1
      nombre=Servidor B1
      tipo=producción
  productos[1]
    id = PRODB2
    nombre = Producto B2
    servidores[0]
      id=CLC-SERV-B2
      nombre=Servidor B2
      tipo=producción
    servidores[1]
      id=CLC-SERV-B2B
      nombre=Servidor B2B
      tipo=pruebas
  productos[2]
    id = PRODB3
    nombre = Producto B3
    servidores[0]
      id=CLC-SERV-A
      nombre=Servidor B3
      tipo=producción
dependencias[0]
  id = ClC-DEPA
  nombre = Dependencia A
  solicitantes[0]
    id = CLC-DEPA-SA
    nombre = Solicitante A
  solicitantes[1]
    id = CLC-DEPA-SB
    nombre = Solicitante B
  solicitantes[2]
    id = CLC-DEPA-SC
    nombre = Solicitante C
dependencias[1]
  id = ClC-DEPB
  nombre = Dependencia B
  solicitantes[0]
    id = CLC-DEPB-SA
    nombre = Solicitante A
  solicitantes[1]
    id = CLC-DEPB-SB
    nombre = Solicitante B
  solicitantes[2]
    id = CLC-DEPB-SC
    nombre = Solicitante C
```
## Lista de casos resumida
```
casos[0]
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
  ingeniero
    id = INGA
    nombre = Edson Artiga
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
  ingeniero
    id = INGB
    nombre = Ricardo Jaimes
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
  ingeniero
    id = INGA
    nombre = Edson Artiga
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
  ingeniero
    id = INGB
    nombre = Ricardo Jaimes
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
  ingeniero
    id = INGA
    nombre = Edson Artiga
  Producto
    id = PRODB1
    nombre = Producto B1
```
## Caso

```
id = CASO01
nombre = Pellentesque fermentum dolor. Aliquam quam lectus, facilisis auctor.
fecha
  inicio = 1496088857
  cierre = 1496090887
estado
  id = 1
  nombre = pendiente
cliente
  id = CLB
  nombre = Cliente B
solicitante
  id = CLB-SB
  nombre = Solicitante B
contrato
  id = CLB-CONT01
  nombre = Contrato 1
tipoCaso
  id = ACT-A2  
  nombre = Actividad A2
ingeniero
  id = INGA 
  nombre = Edson Artiga
producto
  id = PRODA2
  nombre = Producto A2
severidad
  id = S04
  nombre = Severidad 4
descripcion = Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti.
actualizaciones[0]
  id = CASO01-UP01
  fecha = 1496088857
  autor = Edson Artiga
  descripcion = Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti.
archivos[0]
  id = CASO01-ADJ01
  fecha = 1496088857
  autor = Edson Artiga
  tipo = pdf
  nombre = reporte.pdf
  descripcion = Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Phasellus hendrerit. Pellentesque aliquet nibh nec urna. In nisi neque, aliquet vel, dapibus id, mattis vel, nisi. Sed pretium, ligula sollicitudin laoreet viverra, tortor libero sodales leo, eget blandit nunc tortor eu nibh. Nullam mollis. Ut justo. Suspendisse potenti.
horas = 8
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

## Evaluación mensual INGA

```
mes=5
año=2017
ingeniero
  id=INGA
  nombre=Edson Artiga
calificaciones[0]
  nombre=seguimiento
  nota=75
calificaciones[1]
  nombre=  Entrega de hojas
  nota=90
calificaciones[2]
  nombre=  documentación
  nota=100
calificaciones[3]
  nombre=  horas efectivas
  nota=80
calificaciones[4]
  nombre=  evaluación del cliente
  nota=85
calificaciones[5]
  nombre=evaluación técnica
  nota=100
calificaciones[6]
  nombre=evaluación general
  nota=70
calificaciones[7]
  nombre=tiempo de solución
  nota=60
```

## Evaluación Anual
```
año=2017
ingeniero
  id=INGA
  nombre=Edson Artiga
  detalleAnual[0]
    mes=1
    nota=98
    calificaciones[0]
      nombre=seguimiento
      nota=75
    calificaciones[1]
      nombre=  Entrega de hojas
      nota=90
    calificaciones[2]
      nombre=  documentación
      nota=100
    calificaciones[3]
      nombre=  horas efectivas
      nota=80
    calificaciones[4]
      nombre=  evaluación del cliente
      nota=85
    calificaciones[5]
      nombre=evaluación técnica
      nota=100
    calificaciones[6]
      nombre=evaluación general
      nota=70
    calificaciones[7]
      nombre=tiempo de solución
      nota=60
  detalleAnual[1]
    mes=2
    nota=80
    calificaciones[0]
       nombre=seguimiento
       nota=75
    calificaciones[1]
       nombre=  Entrega de hojas
       nota=90
    calificaciones[2]
      nombre=  documentación
      nota=100
    calificaciones[3]
      nombre=  horas efectivas
      nota=80
    calificaciones[4]
      nombre=  evaluación del cliente
      nota=85
    calificaciones[5]
      nombre=evaluación técnica
      nota=100
    calificaciones[6]
      nombre=evaluación general
      nota=70
    calificaciones[7]
      nombre=tiempo de solución
      nota=60
  detalleAnual[3]
    mes=4
    nota=99
    calificaciones[0]
      nombre=seguimiento
      nota=75
    calificaciones[1]
      nombre=  Entrega de hojas
      nota=90
    calificaciones[2]
      nombre=  documentación
      nota=100
    calificaciones[3]
      nombre=  horas efectivas
      nota=80
    calificaciones[4]
      nombre=  evaluación del cliente
      nota=85
    calificaciones[5]
      nombre=evaluación técnica
      nota=100
    calificaciones[6]
      nombre=evaluación general
      nota=70
    calificaciones[7]
      nombre=tiempo de solución
      nota=60
  detalleAnual[2]
    mes=3
    nota=95
    calificaciones[0]
      nombre=seguimiento
      nota=75
    calificaciones[1]
      nombre=  Entrega de hojas
      nota=90
    calificaciones[2]
      nombre=  documentación
      nota=100
    calificaciones[3]
      nombre=  horas efectivas
      nota=80
    calificaciones[4]
      nombre=  evaluación del cliente
      nota=85
    calificaciones[5]
      nombre=evaluación técnica
      nota=100
    calificaciones[6]
      nombre=evaluación general
      nota=70
    calificaciones[7]
      nombre=tiempo de solución
      nota=60
```
