# ZG ZoneClans — releases and compatibility

Protected candidate pair: **server 1.1.3 + client 1.1.3** (10 October 2026), author Elgochogms, All Rights Reserved. Not yet uploaded to CurseForge.

- Minecraft 1.20.1, Forge 47.x; isolated server test on Forge 47.4.10 / Java 17.
- Distribution layout: **paired**.
- Required server dependency from current source metadata: **ZoneCore** `[2.0.0,)`; tested with protected 2.1.3. ZoneProtes is optional for land-claim war integration.
- Server SHA-256: `89227DA2F2376DF75F084DA801E289D9B24922BA8A6685623CD1072374EF8AC4`.
- Client SHA-256: `8BCF3EFE4FE21726D84D3D650CDB340AEBAC20CDDED000F21EAF51CB05116526`.
- Version 1.1.3 fixes a shutdown crash when optional ZoneProtes is absent. The protected server started, registered `/clan` commands, and stopped cleanly without ZoneProtes in an isolated Forge server. The protected client has been built and inspected but not launched graphically or joined to the server. Do not infer full pair compatibility from the server smoke test.
- One CurseForge page per functional mod. Client and server files, when present, are uploaded to that same page and labeled with their compatible pair.
- Do not install `-dev`, fixture, test, source or unprotected build JARs.
- Check the final file changelog, SHA-256 and dependency ranges before deploying to a persistent world.

## Español

La pareja protegida es **servidor 1.1.3 + cliente 1.1.3**, con autor Elgochogms y licencia All Rights Reserved; todavía no está subida a CurseForge. Esta versión evita el fallo al apagar el servidor cuando no existe el ZoneProtes opcional. El JAR servidor arrancó con ZoneCore 2.1.3 protegido en Forge 47.4.10, registró `/clan` y se detuvo sin errores. Se compiló e inspeccionó el JAR cliente, pero falta probar su inicio gráfico y conexión con el servidor. Los SHA-256 figuran arriba. No mezcles versiones ni instales JAR `-dev`.

