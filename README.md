# EAMTA 2026 - Analog Design Course TP Final

Trabajo práctico final, diseño de amplificador operacional con tecnologia MOS

## Parámetros

```
.param w857 = 15
.param l857 = 0.9
.param m857 = 1
.param wpar = 45
.param lpar = 0.45
.param mpar = 20
.param w34  = 4
.param l34  = 2
.param m34  = 4
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
|$\omega_0$|76.71 MHz|55.43 MHz|74.34 MHz|
|K         |50.66 db |54.69 db |40.39 db |
|pm        |60.32°   |63.71°   |15.31°   |

### Closed Loop

|          |TT       |FF       |SS       |
|:--------:|--------:|--------:|--------:|
|K         |19.72 db |19.81 db |19.18 db |
|$\omega_0$|61.59 MHz|49.12 MHz|67.32 MHz|
|THD       |-44.08 db|-57.81 db|-29.44 db|
|onoise    |259 uV   |243 uV   |-nan     |

## Conclusiones
El diseño no cumple con los requisitos solicitados. Cualquier recomendación
es bienvenida
