# FC Mobile Discord Bot v2

Incluye clubes, sobres de 3 jugadores, monedas, plantilla, formaciones, amistosos simulados, clasificación global, evento diario, tienda y venta de jugadores.

## Estructura requerida
Sube el CONTENIDO de esta carpeta a la raíz del repositorio GitHub. Deben verse `package.json`, `railway.json` y `src/`.

## Railway
1. Crea proyecto desde el repositorio.
2. Añade variables `DISCORD_TOKEN`, `CLIENT_ID`, `GUILD_ID`.
3. Despliega con `npm start`.
4. Registra comandos una vez ejecutando `npm run register` con las mismas variables. Puedes usar la consola de Railway o una ejecución temporal.
5. Para conservar datos crea un Volume montado en `/app/data` y añade `DATA_DIR=/app/data`.

## Seguridad
No subas `.env` ni publiques el token. Si se filtra, regénéralo en Discord Developer Portal.

Los jugadores son ficticios. Proyecto fan-made no afiliado a EA SPORTS. Partidos simulados, no juego en tiempo real.
