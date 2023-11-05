# HoyFio

## Grupo

### Integrantes

- 49740 - José, Agustín

### Repositorios

- [fullstack app](https://github.com/AgusJose02/tp-verano)

## Tema

### Descripción

Página en la que se pueden crear grupos de gastos, donde estos se dividen entre todos los integrantes del grupo (o los seleccionados).
Las deudas se simplifican automáticamente para reducir la cantidad de pagos realizados.

### Modelo

![imagen del modelo](https://github.com/AgusJose02/tp-verano/blob/main/Diagrama%20de%20Tablas%20-%20HoyFio.png)

| Req                     | Detalle                                                                                 |
| :---------------------- | :-------------------------------------------------------------------------------------- |
| CRUD simple             | 1. CRUD Grupo <br>2. CRUD Usuario<br>                                                   |
| CRUD dependiente        | 1. CRUD Gasto {depende de} CRUD Grupo<br>2. CRUD Saldo de deuda {depende de} CRUD Gasto |
| Listado<br>+<br>detalle | 1. Listado de gastos => detalle gasto<br> 2. Listado de grupos => detalle grupo         |
| CUU/Epic                | 1. Crear un Gasto<br>2. Saldar deuda                                                    |
