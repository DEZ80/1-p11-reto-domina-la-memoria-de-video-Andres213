# RETO 1.P11: Domina la memoria de vídeo
Copia más abajo tus programas, cada uno en su parte del reto.

# PROGRAMAS

## Actividad 1: Dibujo de 4x8 píxeles
Las 8 primeras fílas de pantalla, de distintos colores
```
3E FF 32 00 C0 3E 00 32 80 C0 3E F0 32 00 D0
3E 00 32 80 D0 3E 0F 32 00 E0 3E 00 32 80 E0
3E F0 32 00 F0 3E 00 32 80 F0 3E FF 32 50 C0
18 FE 
```
PC: 4000

## Actividad 2: Subrayar 'READY' de colores
8 filas de píxeles de distintos colores subrayando toda la palabra de Ready (40 píxeles)
```
21 FF FF 22 70 C3 21 FF FF 22 72 C3
21 FF FF 22 74 C3 21 FF FF 22 76 C3
21 FF FF 22 78 C3
21 F0 F0 22 70 CB 21 F0 F0 22 72 CB
21 F0 F0 22 74 CB 21 F0 F0 22 76 CB
21 F0 F0 22 78 CB
21 0F 0F 22 70 D3 21 0F 0F 22 72 D3
21 0F 0F 22 74 D3 21 0F 0F 22 76 D3 
21 0F 0F 22 78 D3 
21 00 00 22 70 DB 21 00 00 22 72 DB 
21 00 00 22 74 DB 21 00 00 22 76 DB 
21 00 00 22 78 DB 
21 00 00 22 70 E3 21 00 00 22 72 E3
21 00 00 22 74 E3 21 00 00 22 76 E3
21 00 00 22 78 E3 
21 0F 0F 22 70 EB 21 0F 0F 22 72 EB
21 0F 0F 22 74 EB 21 0F 0F 22 76 EB 
21 0F 0F 22 78 EB 
21 F0 F0 22 70 F3 21 F0 F0 22 72 F3
21 F0 F0 22 74 F3 21 F0 F0 22 76 F3
21 F0 F0 22 78 F3 
21 FF FF 22 70 FB 21 FF FF 22 72 FB
21 FF FF 22 74 FB 21 FF FF 22 76 FB
21 FF FF 22 78 FB
18 FE
```
PC: 4000

## Actividad 3: Rectángulo de 2 colores y 2 píxeles de ancho
Alrededor del texto `1.1` que va después de BASIC.
```
21 FF FF 22 DE C2 21 FF FF 22 DF C2
21 FF FF 22 E1 C2 21 FF FF 22 E2 C2
21 FF FF 22 DE CA 21 FF FF 22 DF CA
21 FF FF 22 E1 CA 21 FF FF 22 E2 CA
21 FF FF 22 3E F2 21 FF FF 22 3F F2 
21 FF FF 22 40 F2 21 FF FF 22 42 F2
21 FF FF 22 3E FA 21 FF FF 22 3F FA
21 FF FF 22 40 FA 21 FF FF 22 42 FA
21 00 0F 22 3C FA 21 00 0F 22 8C C2
21 00 0F 22 8C CA 21 00 0F 22 8C CA
21 00 0F 22 8C D2 21 00 0F 22 8C DA
21 00 0F 22 8C E2 21 00 0F 22 8C EA
21 00 0F 22 8C F2 21 00 0F 22 8C FA
21 00 0F 22 DC C2 21 00 0F 22 DC CA 
21 00 0F 22 3C F2 
21 0F 00 22 44 FA 21 0F 00 22 94 C2
21 0F 00 22 94 CA 21 0F 00 22 94 D2 
21 0F 00 22 94 DA 21 0F 00 22 94 E2 
21 0F 00 22 94 EA 21 0F 00 22 94 F2
21 0F 00 22 94 FA 21 0F 00 22 E4 C2
21 0F 00 22 E4 CA 21 0F 00 22 44 F2
18 FE
```
PC: 4000

## Actividad 4: Cara de un dado de 8x7 píxeles
Debe estar, más o menos, en el centro de la pantalla (no tiene porqué ser exacto)
```
21 0F 0F 22 95 C3 21 6F 6F 22 95 CB
21 0F 0F 22 95 D3 21 6F 6F 22 95 DB
21 0F 0F 22 95 E3 21 6F 6F 22 95 EB 
21 0F 0F 22 95 F3 
18 FE
```
PC: 4000

# IMAGENES
Si quieres, puedes subir pantallazos y enlazarlos aquí.
![Actividad 1](/tuimagen1.png)
![Actividad 2](/tuimagen2.png)
![Actividad 3](/tuimagen3.png)
![Actividad 4](/tuimagen4.png)

