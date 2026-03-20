# EAMTA 2026 - Analog Design Course TP Final

Trabajo práctico final, diseño de amplificador operacional con tecnologia MOS

## Parámetros

```
.param w857 = 15
.param l857 = 0.9
.param m857 = 1.2
.param wpar = 30
.param lpar = 0.45
.param mpar = 15
.param w34  = 6
.param l34  = 2
.param m34  = 6
.param w6   = 20
.param l6   = 1.5
.param m6   = 15

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
|$\omega_0$|66.03 MHz|61.95 MHz|69.31 MHz|
|K         |53.71 db |56.13 db |47.19 db |
|pm        |51.19°   |60.07°   |49.06°   |

### Closed Loop

|          |TT       |FF       |SS       |
|:--------:|--------:|--------:|--------:|
|K         |19.77 db |19.84 db |19.55 db |
|$\omega_0$|58.14 MHz|54.14 MHz|64.29 MHz|
|THD       |-43.89 db|-56.74 db|-29.71 db|
|onoise    |295 uV   |270 uV   |494 uV   |

## Conclusiones

En TT hay que acomodar pm, thd y $\omega_0$ en cl  
En FF hay que acomodar $\omega_0$ en cl 
En SS hay que acomodar ruido, thd pm y gain  
