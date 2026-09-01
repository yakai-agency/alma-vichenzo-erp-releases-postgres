# alma-vichenzo-erp-releases-postgres

Instaladores del track de migración a Postgres de Alma Vichenzo ERP.

**Aislado a propósito** del canal de producción
([alma-vichenzo-erp-releases](https://github.com/yakai-agency/alma-vichenzo-erp-releases),
el que usa el negocio hoy, arquitectura SQLite multi-master). Este repo
solo recibe releases del workflow `release-postgres.yml` (disparo manual,
`workflow_dispatch`), nunca del `release.yml` de producción.

No usar todavía para operar el negocio real: falta resolver la
distribución de la credencial de Postgres (`APP_ERP_PASSWORD`) y el
certificado TLS del pooler antes de un piloto de verdad — ver la Fase E/H
de `prancy-spinning-squid.md` en el repo fuente.

Sin código fuente — ver el repo privado `alma-vichenzo-erp`.
