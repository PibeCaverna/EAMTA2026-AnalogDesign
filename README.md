# EAMTA 2026 - Analog Design Course
# TP FInal

Trabajo práctico final, diseño de amplificador operacional con tecnologia MOS

## Open Loop

- gbw ancho de banda ganancia
- dcg ganancia dc
- pm margen de fase
- gm margen de ganancia

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
