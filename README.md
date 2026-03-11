# EAMTA 2026 - Analog Design Course TP Final

Trabajo práctico final, diseño de amplificador operacional con tecnologia MOS

## Open Loop

- gbw ancho de banda ganancia
- dcg ganancia dc
- pm margen de fase
- gm margen de ganancia
IMPORTANTE: MANTENER EL AR DE M6 y M3 SIMILARES 

### Primer contacto

gm1 = 1 (par diferencial)  
gm6 = 20 ms  
quiero largar 200uA al par y 2mA a la salida  
multiplicador x2 a M5 y x20 a M7 (parametro mult en los Mosfet)  
al principio falla, porque no polariza (transistore muy chicos) ponemos l a x4 y w a x10  
sigue sin funcar porque el resto de transistores están a tamaño mínimo, procedemos a agrandar  
para aumentar el cruce por cero, podemos mover el gm1

## Closed Loop

Gain = 20db  
A = 1/B (aprox)  
Ri = 500 -> Rf = Gain x Ri = 5000  

## Corners

Cambiar Vdd, Vcm, Iref, temperatura y modelos  
tiene que cumplir especificaciones para los 3 corners en los dos benches (6 simulaciones).  
ahora cumplimos TT y FF, falta SS

## Parámetros

´´´
.param w857 = 15
.param l857 = 0.9
.param m857 = 1
.param wpar = 20
.param lpar = 0.35
.param mpar = 4
.param w34  = 4
.param l34  = 0.9
.param m34  = 6
.param w6   = 20
.param l6   = 0.9
.param m6   = 24

´´´

## Resultados

### TT

#### Open Loop
$\omega_0 = 82.8e+06$  
$K        = 54.25 db$  
$pm       = 56.58°  $ 

### Closed Loop

$K        = 19.8 db  $
$\omega_0 = 69.4e+06 $  
$THD      = -52.46 db$  
$onoise   = 5.85e-04 $  

### FF

#### Open Loop
$\omega_0 = 73.2e+06$  
$K        = 56.78 db$  
$pm       = 61.86°  $ 

### Closed Loop

$K        = 19.8 db  $
$\omega_0 = 64.71e+06$  
$THD      = -64.43 db$  
$onoise   = 5.54e-04 $  

### SS

#### Open Loop
$\omega_0 = 85.65e+06$  
$K        = 51.38 db $  
$pm       = 16.68°   $ 

### Closed Loop

$K        = 19.7 db  $
$\omega_0 = 87.83e+06$  
$THD      = -39.34 db$  
$onoise   = 7.75e-04 $  
