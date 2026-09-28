PORTAL CITATORIOS.EDUPSIC.COM

Archivos para GitHub Pages:
- index.html
- CNAME

1. En index.html reemplaza:
   PEGA_AQUI_TU_URL_EXEC
   por la URL /exec de tu implementación actual de Apps Script.

2. Sube index.html y CNAME a un repositorio de GitHub Pages.

3. En el DNS de edupsic.com crea el CNAME:
   Host: citatorios
   Destino: TU_USUARIO.github.io

4. En GitHub > Settings > Pages configura:
   Custom domain: citatorios.edupsic.com
   Enforce HTTPS: activado cuando esté disponible.

5. Los enlaces que genera Apps Script quedarán así:
   https://citatorios.edupsic.com/?c=CODIGO_PUBLICO
