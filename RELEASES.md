# ZoneClans — releases and compatibility

Protected Beta pair: **server 1.1.4 + client 1.1.4** (10 October 2026), author Elgochogms, All Rights Reserved. Uploaded to the **same CurseForge project** as server file [9124543](https://authors.curseforge.com/#/projects/1738046/files/9124543) and client file [9124556](https://authors.curseforge.com/#/projects/1738046/files/9124556). Moderation and public availability are pending.

- Minecraft 1.20.1, Forge 47.x; isolated server test on Forge 47.4.10 / Java 17.
- Distribution layout: **paired**.
- Required server dependency from current source metadata: **ZoneCore** `[2.0.0,)` and **ZoneCrates** `[2.0.1,3)`; tested with protected ZoneCore 2.1.3 and ZoneCrates 2.0.5. ZoneProtes is optional for land-claim war integration.
- Server SHA-256: `0854402ECD43E772D51EE94847DE9BB291D14AE44CA8F3174D8B3AF2C4007A36`.
- Client SHA-256: `5A420B4F046AF8CC142460092CF216EEA2FC90AE1D0AED459FE6D9ED82ABD4F0`.
- Version 1.1.4 includes the shutdown fix when optional ZoneProtes is absent and formally declares ZoneCrates as required for server banking. The protected server started, registered `/clan` commands, and stopped cleanly without ZoneProtes in an isolated Forge server. The protected client has been built and inspected but not launched graphically or joined to the server. Do not infer full pair compatibility from the server smoke test.
- One CurseForge page per functional mod. Client and server files, when present, are uploaded to that same page and labeled with their compatible pair.
- Do not install `-dev`, fixture, test, source or unprotected build JARs.
- Check the final file changelog, SHA-256 and dependency ranges before deploying to a persistent world.

## Español

La pareja protegida Beta es **servidor 1.1.4 + cliente 1.1.4**, con autor Elgochogms y licencia All Rights Reserved. Ambos archivos están cargados en **un solo proyecto CurseForge** con los IDs 9124543 y 9124556; falta la moderación y la disponibilidad pública. Esta versión evita el fallo al apagar el servidor cuando no existe el ZoneProtes opcional. El JAR servidor arrancó con ZoneCore 2.1.3 protegido y ZoneCrates 2.0.5 en Forge 47.4.10, registró `/clan` y se detuvo sin errores. Se compiló e inspeccionó el JAR cliente, pero falta probar su inicio gráfico y conexión con el servidor. Los SHA-256 figuran arriba. No mezcles versiones ni instales JAR `-dev`.

