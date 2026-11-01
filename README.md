# Portfolio — DTCSync Server — APIs centrais

> Public case study only. **No source code** is published here (client/production systems remain private).  
> Estudo de caso público. **Sem código-fonte** (sistemas de cliente/produção permanecem privados).  
> Caso de estudio público. **Sin código fuente** (sistemas de cliente/producción permanecen privados).

---

## 🇧🇷 Português

### DTCSync Server — APIs centrais

**Role / Papel / Rol:** Backend e camada de APIs da operação  
**Stack:** `Python, HTML/JS, REST APIs, PostgreSQL`

#### Problem / Problema
Vários módulos (sync, dashboard, portal) precisavam de um ponto central de APIs para autenticação, dados e regras de negócio — sem espalhar lógica em cada cliente.

#### Solution / Solução / Solución
Implementei o servidor que concentra as APIs usadas pelos agentes e painéis, com endpoints versionáveis e integração com o ecossistema DTCSync.

#### Highlights
- Hub de APIs para múltiplos clientes
- Integração com agente e dashboards
- Stack web + Python


---

## 🇬🇧 English

### DTCSync Server — central APIs

**Role / Papel / Rol:** Backend and operational API layer  
**Stack:** `Python, HTML/JS, REST APIs, PostgreSQL`

#### Problem / Problema
Multiple modules needed a central API layer for auth, data, and business rules instead of duplicating logic in every client.

#### Solution / Solução / Solución
I implemented the server that hosts APIs consumed by agents and dashboards, with versionable endpoints integrated into the DTCSync ecosystem.

#### Highlights
- API hub for multiple clients
- Integration with agent and dashboards
- Web + Python stack


---

## 🇪🇸 Español

### DTCSync Server — APIs centrales

**Role / Papel / Rol:** Backend y capa de APIs operativas  
**Stack:** `Python, HTML/JS, REST APIs, PostgreSQL`

#### Problem / Problema
Varios módulos necesitaban un punto central de APIs para autenticación, datos y reglas de negocio.

#### Solution / Solução / Solución
Implementé el servidor que concentra las APIs usadas por agentes y paneles, con endpoints versionables e integración con DTCSync.

#### Highlights
- Hub de APIs para varios clientes
- Integración con agente y dashboards
- Stack web + Python


---

## Notes / Observações / Notas

- Author: **Douglas Francisco Bonfim**
- Related private implementation (not public): `dtcsync-server`
- No credentials, customer data, hostnames, or proprietary payloads are included in this document.
