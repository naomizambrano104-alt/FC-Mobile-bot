# FC Mobile — Bot de Discord

Bot inicial de fútbol con packs, plantilla, tienda, monedas, perfil y amistosos simulados.

## Requisitos
- Node.js 20 o superior
- Una aplicación/bot creado en Discord Developer Portal
- Un servidor de Discord donde tengas permiso para instalar aplicaciones

## Instalación
1. Descomprime el proyecto.
2. Abre una terminal dentro de la carpeta.
3. Ejecuta `npm install`.
4. Copia `.env.example` a `.env`.
5. Completa `DISCORD_TOKEN`, `CLIENT_ID` y `GUILD_ID`.
6. Ejecuta `npm run register`.
7. Ejecuta `npm start`.

## Crear el bot en Discord
1. Entra en https://discord.com/developers/applications
2. Crea una aplicación llamada FC Mobile.
3. En la sección **Bot**, crea el bot y copia su token.
4. En **OAuth2 > URL Generator**, marca `bot` y `applications.commands`.
5. Dale permiso para enviar mensajes e insertar enlaces/embeds.
6. Usa la URL generada para invitarlo a tu servidor.

**Importante:** nunca compartas tu token ni lo pegues en un chat. Si se filtra, regénéralo desde Developer Portal.

## Comandos iniciales
- `/inicio club:<nombre>`
- `/perfil`
- `/pack`
- `/plantilla`
- `/tienda`
- `/comprar numero:<1-4>`
- `/amistoso rival:@usuario`

## Estado de esta versión
Es una base jugable para probar en un servidor. Los partidos son simulaciones por GRL, no un videojuego en tiempo real. La liga, eventos, alineación táctica, mercado entre usuarios, temporadas y protecciones anti-abuso quedan para las siguientes versiones. La base SQLite guarda datos localmente en `data.sqlite`; para alojarlo 24/7 se necesitará un servidor/hosting persistente.
