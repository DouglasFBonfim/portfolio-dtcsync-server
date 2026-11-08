# Portfolio — DTCSync Server — APIs centrais

> Public case study only. **No source code** is published here (client/production systems remain private).  
> Estudo de caso público. **Sem código-fonte** (sistemas de cliente/produção permanecem privados).  
> Caso de estudio público. **Sin código fuente** (sistemas de cliente/producción permanecen privados).

---

## 🇧🇷 Português

### DTCSync Server — hub de APIs da operação

**Role / Papel / Rol:** Backend e camada de APIs da operação  
**Stack:** `Python, FastAPI/Flask, REST, PostgreSQL, VPN, bandeja Windows`

#### Problem / Problema
Agente, Client desktop, Android e painéis precisam de um ponto único para módulos, credenciais, execuções fiscais (NF-e/NFC-e), cadastro de aparelhos e regras — sem duplicar lógica em cada ponta.

#### Solution / Solução / Solución
Servidor central que expõe APIs consumidas pelo agente e pelos clientes (desktop/Android), com flags de execução fiscal, integração VPN/reserva, empacotamento Windows (tray) e endpoints usados por Dashboard, PontoBR e Portal.

#### Highlights
- Hub de APIs para múltiplos clientes e canais (agente / Client / Android)
- Flag de execuções NF-e / NFC-e consultável na ponta
- Integração VPN e operação contínua (launcher em bandeja)
- Stack web + Python empacotável


---

## 🇬🇧 English

### DTCSync Server — central API hub

**Role / Papel / Rol:** Backend and operational API layer  
**Stack:** `Python, FastAPI/Flask, REST, PostgreSQL, VPN, Windows tray`

#### Problem / Problema
Agent, desktop Client, Android and panels need one place for modules, credentials, fiscal execution flags (NF-e/NFC-e), device enrollment and rules — without duplicating logic on every edge.

#### Solution / Solução / Solución
A central server exposing APIs for the agent and clients (desktop/Android), with fiscal execution flags, VPN/fallback integration, Windows tray packaging and endpoints used by Dashboard, PontoBR and Portal.

#### Highlights
- API hub for multiple clients and channels (agent / Client / Android)
- NF-e / NFC-e execution flags readable at the edge
- VPN integration and always-on tray launcher
- Packaged web + Python stack


---

## 🇪🇸 Español

### DTCSync Server — hub de APIs operativas

**Role / Papel / Rol:** Backend y capa de APIs operativas  
**Stack:** `Python, FastAPI/Flask, REST, PostgreSQL, VPN, bandeja Windows`

#### Problem / Problema
Agente, Client, Android y paneles necesitan un punto único para módulos, credenciales, ejecuciones fiscales y reglas.

#### Solution / Solução / Solución
Servidor central con APIs para agente y clientes, flags de ejecución NF-e/NFC-e, VPN, empaquetado en bandeja Windows y endpoints de Dashboard/PontoBR/Portal.

#### Highlights
- Hub de APIs multi-cliente y multi-canal
- Flags de ejecución fiscal en la punta
- VPN y launcher en bandeja
- Stack web + Python empaquetable


---

## Notes / Observações / Notas

- Author: **Douglas Francisco Bonfim**
- Related private implementation (not public): `dtcsync-server`
- Companion cases: `dtcsync`, `dtcsyncclient`, `dtcsyncandroid`
- No credentials, customer data, hostnames, or proprietary payloads are included in this document.
