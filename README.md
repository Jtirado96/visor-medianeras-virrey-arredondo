# Muros medianeros – Virrey Arredondo y Enrique Martínez

Visor web (Potree 1.8) de la nube de puntos `virreyarredondo-murosmedianeros_ajustada_ET.laz`,
reducida a 1 punto cada 1 cm (22,0 millones de puntos).

**Coordenadas:** sistema local de la estación total (`V Arredondo 3345.dwg`), en metros, Z vertical.
La nube se ajustó en planta a los puntos de muro relevados con ET y en altura a PV1, PV2, PV3 y PV4
(residuos en los PV entre 0,5 y 4,4 cm). Los DXF exportados salen en esas mismas coordenadas.
No incluye Medianera5.

**Cortes → DXF** (panel arriba a la derecha):
- *Por tramos de muro*: «1 · Marcar tramo de muro» (dos clics sobre la pared, desde cualquier vista) crea una caja alineada con el muro; «2 · Cortar el tramo a la cota Z» la reduce a la faja de corte. Sólo se lee esa parte de la nube.
- *Mover el corte*: una vez cortado, la cota se cambia con el control deslizante, con Shift + rueda (1 cm; Shift + Alt: 10 cm) o con la flecha azul de la caja.
- *Zoom*: la rueda acerca hacia el punto bajo el cursor, hasta pocos centímetros de la pared.
- *Corte horizontal de todo el predio*: planta a la cota Z (ET) y espesor elegidos (piso ≈ −0,5 m).
- *Caja libre*: se crea horizontal envolviendo toda la nube; cada cubo de color mueve una sola cara (X, Y, arriba/abajo) y sólo gira sobre Z, así la base queda siempre horizontal. También se puede fijar Z inferior/superior, ancho, profundidad y giro con valores.
- Proyecciones: Planta (X, Y), Alzado según la caja (distancia, altura) o 3D.
- El DXF se genera en el navegador a máxima resolución disponible (1 cm), raleado a 1 cm, como puntos en capa `CORTE_*`.

Visor: [Potree](https://github.com/potree/potree) (licencia BSD-2, ver `POTREE_LICENSE`).
