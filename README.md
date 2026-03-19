# EAMTA 2026 - Analog Design Course TP Final

Trabajo práctico final, diseño de amplificador operacional con tecnologia MOS

## Parámetros

```
.param w857 = 15
.param l857 = 0.9
.param m857 = 1
.param wpar = 30
.param lpar = 0.45
.param mpar = 15
.param w34  = 6
.param l34  = 2
.param m34  = 6
.param w6   = 20
.param l6   = 1
.param m6   = 10

```
### Compensación

```
M9
L = 0.4 W = 3
nf = 1 mult = 3

C1
m = 1 value = 3.8p
```

## Resultados

### Open Loop

|          |TT       |FF       |SS       |
|:--------:|--------:|--------:|--------:|
|$\omega_0$|81.04 MHz|55.18 MHz|93.93 MHz|
|K         |52.14 db |55.46 db |46.18 db |
|pm        |62.59°   |66.63°   |-24.87°  |

### Closed Loop

|          |TT       |FF       |SS       |
|:--------:|--------:|--------:|--------:|
|K         |19.74 db |19.83 db |19.49 db |
|$\omega_0$|65.94 MHz|49.28 MHz|83.79 MHz|
|THD       |-45.51 db|-58.80 db|-32.17 db|
|onoise    |298 uV   |272 uV   |-nan     |

## Conclusiones

Hay que corregir el thd en TT  
Está caida la w0 dde FF en ambos loops  
le falta ganancia a SS, el pm está negativo  
