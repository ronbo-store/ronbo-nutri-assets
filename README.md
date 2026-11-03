# ronbo-nutri-assets
## Fuentes y licencias / Sources & licenses

- `E003_2f.gif`, `E008_2f.gif`, `E018_2f.gif`, `E019_2f.gif`, `E023_2f.gif`, `E090_2f.gif` — free-exercise-db (Unlicense / dominio público).
- `E104.png` — Everkinetic, CC BY-SA 3.0, vía Wikimedia Commons («Dumbbell-bent-arm-pullover-1.png»).
- `E105.jpg`, `E106.jpg` — free-exercise-db, Unlicense / dominio público (dataset público de ejercicios).
- `E107.jpg` — Tpikonen, CC BY-SA 4.0, vía Wikimedia Commons («Captains chair.jpg», redimensionada a 800 px).
- `E109.jpg` — Producción propia de Ronald Borges (imagen hecha por él, aportada por correo el 2026-10-26; original PNG 1254×1254, versión web redimensionada a 1000 px).
- `E024.jpg` — Rehospedada el 2026-10-28 desde thebarbell.com (era el hotlink de la ficha; sin CORS en origen) por autorización expresa de Ronald, para que la tarjeta para compartir pueda pintarla.
- `E038.png`, `E082.png` — Rehospedadas el 2026-10-28 desde budy-fitness-assets (S3; ilustraciones anatómicas; eran los hotlinks de las fichas, sin CORS en origen), misma autorización.
- `E045.webp`, `E068.png` — Rehospedadas el 2026-10-28 desde fitnessvolt.com (ilustraciones; eran los hotlinks de las fichas, sin CORS en origen), misma autorización.
- `E096.webp` — Rehospedada el 2026-10-28 desde el catálogo liftag (S3; era el hotlink de la ficha, sin CORS en origen), misma autorización.
- `E100.webp` — Rehospedada el 2026-10-28 desde uncomo.com (secuencia de 3 fotos; era el hotlink de la ficha, sin CORS en origen), misma autorización.

## Estándar de imágenes de la Biblioteca (desde 2026-11-02)

- Toda imagen nueva de ficha o variante entra por el flujo `flujo_imagen_biblioteca.py` (carpeta del mecanismo en el proyecto): cualquier formato y orientación → **WebP 1920×1280 (proporción 1.5)** → **menos de 200 KB** a la mayor calidad que quepa. Política de ajuste: recorte «cover» centrado en horizontal con ancla vertical al 40 % desde arriba; sin bandas ni rellenos.
- Nombres en la raíz: foto principal `E###.webp`; variante `E###-<slug>.webp`.
- Enlace directo estable: `https://ronbo-store.github.io/ronbo-nutri-assets/<nombre>`.
- A este repo solo entra la versión final optimizada; el original pesado no se guarda aquí.
- Lote 2026-11-02 — imágenes generadas por IA, aportadas por Ronald Borges por correo el 2026-11-02: `E051-pies-anchos/estrechos/estandar/altos/bajos.webp` (5 variantes de Prensa de piernas), `E003-torso-atras/erguido/adelante.webp` (3 variantes de Mariposa en máquina — pec deck; la de torso erguido incluye la flecha que marca la posición), `E004-press-de-pie/sentado.webp` y `E004-aperturas-de-pie/sentado.webp` (pecho en poleas).
