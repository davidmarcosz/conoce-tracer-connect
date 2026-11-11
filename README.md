# conoce.tracer-connect.com

Landing de Tracer Connect.

- `index.html`: landing principal.
- `gracias.html`: página de agradecimiento.
- `assets/reels/`: reels verticales (9:16) del carrusel "Tracer Connect en 60 segundos".

## Agregar o cambiar un reel

1. Copie el MP4 a `assets/reels/`.
2. En `index.html`, busque la lista `const all = [...]` y ponga la ruta en el campo `video` del reel.
   Los reels con `video` vacío no se muestran.

## Verla en local

```bash
npx http-server@14.1.1 . -p 5175 -c-1
```
