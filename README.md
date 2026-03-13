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
.param m6   = 24

```
### Compensación

```
M9
L = 0.4 W = 3
nf = 1 mult = 3

C1
m = 1 value = 3.3p
```

## Resultados

### TT

#### Open Loop
$\omega_0 = 62.38 Mhz$  
$K        = 55.92 db$  
$pm       = 62°     $ 

### Closed Loop

$K        = 19.84 db $
$\omega_0 = 52.9 Mhz$  
$THD      = -51.44 db$  
$onoise   = 271 \mu V$  

### FF

#### Open Loop
$\omega_0 = 62.12 MHz$  
$K        = 58.99 db $  
$pm       = 56.76°   $ 

### Closed Loop

$K        = 19.89 db $
$\omega_0 = 54.61 MHz$  
$THD      = -63.9 db $  
$onoise   = 256 \mu V$  

### SS

#### Open Loop
$\omega_0 = 65.94 MHz$  
$K        = 46.79 db $  
$pm       = 42.20°   $  

### Closed Loop

$K        = 19.69 db $  
$\omega_0 = 58.8 MHz $  
$THD      = -38.65 db$  
$onoise   = -nan     $  

## Conclusiones
El diseño no cumple con los requisitos solicitados. Cualquier recomendación
es bienvenida
