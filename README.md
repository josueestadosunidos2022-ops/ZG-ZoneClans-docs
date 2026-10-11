# ZG ZoneClans

## English

Clans with ranks, a GodieCoin bank, wars and weekly rewards. Minecraft 1.20.1 / Forge 47.x.

### Installation

Install **server 1.1.3** on the dedicated server and **client 1.1.3** on players' clients. Both files belong to this one CurseForge project; do not install the server JAR on a client. Required dependency: **ZoneCore** `[2.0.0,)` on the server. The protected server JAR was smoke tested with protected ZoneCore 2.1.3. ZoneProtes is optional for land-claim war integration; without it, clans still start and stop normally. Bank payments also need the compatible ZONE economy provider configured on the server.

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

Instala **servidor 1.1.3** en el servidor dedicado y **cliente 1.1.3** en los clientes. Ambos archivos van en este único proyecto CurseForge; no instales el JAR de servidor en el cliente. Dependencia obligatoria: **ZoneCore** `[2.0.0,)` en el servidor. El JAR servidor protegido se probó con ZoneCore 2.1.3 protegido. ZoneProtes es opcional para integrar las guerras con protecciones; sin él, los clanes arrancan y se detienen normalmente. Los pagos bancarios también requieren el proveedor de economía ZONE compatible configurado en el servidor.

### Configuración

Edita los TOML generados con el servidor o juego detenido, salvo que exista un comando de recarga documentado. Respalda los datos persistentes antes de actualizar.

| Archivo de configuración | Uso |
|---|---|
| `config/zonaclans-common.toml` | Opciones editables generales, economía, guerras, permisos y premios. |
| `config/ZONEMODS/zonaclans/clanes/resumen.toml` | Exportación legible de datos del mundo; no se edita como configuración. |

Consulta la [referencia de configuración](CONFIGURATION.md) para claves detectadas en el código y la [compatibilidad de entregas](RELEASES.md) para las parejas de versiones.

## Ownership / Titularidad

Documentation and original ZONE visual assets © Elgochogms. This repository contains documentation and a project avatar only; it does not distribute mod source code, private mappings, server secrets or production configuration.

