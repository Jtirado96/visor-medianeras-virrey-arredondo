# Muros medianeros – Virrey Arredondo y Enrique Martínez

Visor web (Potree 1.8) de la nube de puntos `virreyarredondo-murosmedianeros_ajustada_ET.laz`,
reducida a 1 punto cada 1 cm (22,0 millones de puntos).

**Coordenadas:** sistema local de la estación total (`V Arredondo 3345.dwg`), en metros, Z vertical.
La nube se ajustó en planta a los puntos de muro relevados con ET y en altura a PV1, PV2, PV3 y PV4
(residuos en los PV entre 0,5 y 4,4 cm). Los DXF exportados salen en esas mismas coordenadas.
No incluye Medianera5.

**Cortes → DXF** (panel arriba a la derecha):
- *Corte horizontal*: planta a la cota Z (ET) y espesor elegidos (piso ≈ −0,5 m).
- *Caja libre*: para alzados o sectores; se mueve, escala y gira con los controles.
- Proyecciones: Planta (X, Y), Alzado según la caja (distancia, altura) o 3D.
- El DXF se genera en el navegador a máxima resolución disponible (1 cm), raleado a 1 cm, como puntos en capa `CORTE_*`.

Visor: [Potree](https://github.com/potree/potree) (licencia BSD-2, ver `POTREE_LICENSE`).
