# Laberinto + Robot (v2.0)

Este sitio muestra el simulador del curso (v2.0).  
En escritorio se ven **Laberinto + Editor** a la vez. En móvil aparecen pestañas **Laberinto / Editor**.

## Controles
- **Run**: ejecutar en bucle (pausa/continúa)
- **Step**: ejecutar un ciclo
- **Stop**: parar y reiniciar el robot/marcas (mantiene el laberinto)
- **Generar**: crear un laberinto nuevo
- **Inspección**: mostrar/ocultar inspector

## Lenguaje del robot

Comentarios: líneas que empiezan con `#`.

Órdenes:
- `AVANZA`
- `ORIENTATE` (mano izquierda: izq → frente → der → atrás, solo a casillas no andadas)
- `GIRA` (giro 90º horario)
- `OVILLO`
- `RECOGE`

Condicionales (BIF = nº de salidas **no andadas**):
- `EN BIFURCACION <ORDEN>`  (equivale a BIF>1)
- `EN BIFURCACION=1 <ORDEN>`
- `EN BIFURCACION>1 <ORDEN>`
- `EN CALLEJON <ORDEN>` (BIF=0)

> Nota: La ruta solución del laberinto se muestra/oculta haciendo click sobre el laberinto.

---

## Simulador

<div style="width:100%; height:82vh; border:1px solid #1f2a3a; border-radius:12px; overflow:hidden;">
  <iframe src="app.html" style="width:100%; height:100%; border:0;"></iframe>
</div>

Si el iframe no se muestra, abre directamente: **app.html**
