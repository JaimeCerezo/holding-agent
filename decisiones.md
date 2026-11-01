# Decisiones de holding

Lo que no se revierte por descuido, con fecha y porqué. La más reciente arriba.

## 2026-11-01 — Nace holding como subagente de Aris, con repo propio y privado

**Qué**: la información de las sociedades vive en su propio repo privado
(`/srv/projects/holding-agent`), no en el de Aris ni en el de sysops.
**Por qué**: en GitHub los permisos van por repo entero; mezclarlo con otro
repo haría que quien lea ese repo lo lea todo, ahora y el día que se comparta.
**Límite asumido**: sysops tiene `sudo` en la misma máquina y técnicamente
puede leer este repo. La frontera de aislamiento real es la máquina.
