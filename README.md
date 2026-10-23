# ZoneClans

## Current update / Actualización actual — 2026-10-23

Protected public builds prepared for Minecraft 1.20.1 / Forge 47.4.x / Java 17. Files become available after CurseForge approval. / Compilaciones públicas protegidas; los archivos estarán disponibles cuando CurseForge los apruebe.

Updates the clan interfaces and fixes text clipping, wrapping and rank-header layout. Keeps clan saved data and the clans-2 protocol.

| Side / Lado | Version / Versión | File / Archivo |
|---|---|---|
| server | 1.2.1 | `zonaclans-server-1.2.1-protected.jar` |
| client | 1.2.1 | `zonaclans-client-1.2.1-protected.jar` |

Install only the JAR for each side; never put both side JARs in one mods folder. Back up the world and preserve existing player data and TOML files. / Instala solo el JAR correspondiente a cada lado; conserva mundo, progreso y TOML existentes.

**server dependencies / dependencias:** ZoneCore: Required Dependency ([2.0.0,)); ZoneCrates: Required Dependency ([2.0.1,3)); ZoneProtes: Optional Dependency (claim integration).

**client dependencies / dependencias:** No additional Zone dependency / Sin dependencia adicional de Zone.

Archive checks and isolated dedicated-server startup do not certify graphical gameplay, real multiplayer or the full modpack. / Las verificaciones de archivo y arranque aislado no certifican cliente gráfico, multijugador real ni modpack completo.

## Earlier reference / Referencia anterior

The following reference predates this update. Use the current versions and side instructions above when they differ. / La referencia siguiente es anterior; prevalecen las versiones y las indicaciones de lado de esta actualización.

## English

Clans with ranks, a GodieCoin bank, wars and weekly rewards. Minecraft 1.20.1 / Forge 47.x.

### Installation

Install **server 1.1.4** on the dedicated server and **client 1.1.4** on players' clients. Both files belong to this one CurseForge project; do not install the server JAR on a client. Required server dependencies: **ZoneCore** `[2.0.0,)` and **ZoneCrates** `[2.0.1,3)`. The protected server JAR was smoke tested with protected ZoneCore 2.1.3 and ZoneCrates 2.0.5. ZoneProtes is optional for land-claim war integration; without it, clans still start and stop normally.

### Configuration

Edit generated TOML files while the server or game is stopped unless a documented reload command is available. Back up persistent data before updates.

| Config file | Use |
|---|---|
| `config/zonaclans-common.toml` | Editable general, economy, war, permission and prize settings. |
| `config/ZONEMODS/zonaclans/clanes/resumen.toml` | Readable export of world data; do not edit it as configuration. |

See [configuration reference](CONFIGURATION.md) for keys detected in source and [release compatibility](RELEASES.md) for version-pair rules.

## Español

Clanes con rangos, banco de GodieCoins, guerras y premios semanales. Minecraft 1.20.1 / Forge 47.x.

### Instalación

Instala **servidor 1.1.4** en el servidor dedicado y **cliente 1.1.4** en los clientes. Ambos archivos van en este único proyecto CurseForge; no instales el JAR de servidor en el cliente. Dependencias obligatorias del servidor: **ZoneCore** `[2.0.0,)` y **ZoneCrates** `[2.0.1,3)`. El JAR servidor protegido se probó con ZoneCore 2.1.3 protegido y ZoneCrates 2.0.5. ZoneProtes es opcional para integrar las guerras con protecciones; sin él, los clanes arrancan y se detienen normalmente.

### Configuración

Edita los TOML generados con el servidor o juego detenido, salvo que exista un comando de recarga documentado. Respalda los datos persistentes antes de actualizar.

| Archivo de configuración | Uso |
|---|---|
| `config/zonaclans-common.toml` | Opciones editables generales, economía, guerras, permisos y premios. |
| `config/ZONEMODS/zonaclans/clanes/resumen.toml` | Exportación legible de datos del mundo; no se edita como configuración. |

Consulta la [referencia de configuración](CONFIGURATION.md) para claves detectadas en el código y la [compatibilidad de entregas](RELEASES.md) para las parejas de versiones.

## Ownership / Titularidad

Documentation and original ZONE visual assets © Elgochogms. This repository contains documentation and a project avatar only; it does not distribute mod source code, private mappings, server secrets or production configuration.
