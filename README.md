# OPERATION REWIND — Escape Room Digital
## Capgemini Invent · Enterprise Transformation

---

## CÓMO SUBIR A GITHUB PAGES (10 minutos)

1. Crea un repositorio en GitHub (público) llamado `operation-rewind`
2. Sube los 7 archivos HTML:
   - `index.html`
   - `sala-1.html`
   - `sala-2.html`
   - `sala-3.html`
   - `sala-4.html`
   - `sala-5.html`
   - `final.html`
3. Ve a Settings → Pages → Source: "Deploy from branch" → Branch: main → Folder: / (root)
4. En 2-3 minutos tu URL será: `https://TU-USUARIO.github.io/operation-rewind/`

**Comparte esa URL con todos los equipos al mismo tiempo para que empiecen en igualdad.**

---

## CLAVE DE RESPUESTAS (NO COMPARTIR)

| Sala | Puzzle | Respuesta correcta | Código |
|------|--------|-------------------|--------|
| 01 | Frameworks de diagnóstico | Operating Model Canvas + Wardley Map | **BF** |
| 02 | KPI crítico + decisión | Rotación talento senior (B) + Plan retención (1) | **B1** |
| 03 | Stakeholders prioritarios ADKAR | CHRO (2) + Middle Managers (3) + Sindicato (4) | **234** |
| 04 | Punto de quiebre arquitectura IT | On-premise (Decisión 02) | **2** |
| 05 | Workstreams cancelados + niveles governance | 4 cancelados (WS03/05/06/08) + 3 niveles | **43** |

### Workstreams a cancelar (Sala 05):
- **WS03** — Dashboard ejecutivo: sin owner desde agosto
- **WS05** — Benchmarking sectorial: sin budget, paralizado
- **WS06** — Transformación cultural "NexaWay": duplica WS12
- **WS08** — Sostenibilidad corporativa: 0% avance en 8 meses

### Síntomas de governance failure correctos (Sala 05):
- **A** — Más de 40 workstreams en paralelo
- **B** — Steering committee sin actas vinculantes
- **C** — Mismos riesgos en 3 comités sin escalar ni cerrar
(D, E, F son síntomas reales pero secundarios o de metodología, no de governance failure estructural)

---

## LOGÍSTICA DEL EVENTO

### Antes del evento
- [ ] Testea el flujo completo en incógnito (simula un equipo)
- [ ] Comprueba que funciona en móvil
- [ ] Prepara un Google Form de 3 campos: Nombre equipo · Tiempo final · Email
- [ ] Usa ese Form para el ranking (Sheets calcula automáticamente)

### Durante el evento
- Todos los equipos reciben el mismo link al mismo tiempo (por Slack/Teams/email)
- Anuncio verbal: "Tenéis 45 minutos. El ranking es por tiempo. Empezamos en 3, 2, 1..."
- El host monitorea el Google Form para ir anunciando equipos que terminan

### Ranking
El Form con timestamp automático genera el ranking. Ordena por "Marca de tiempo" en Sheets.

---

## VARIANTES SI FALTA TIEMPO

**Si quieres reducir a 30 min:** Elimina Sala 4 (IT Strategy). El flujo queda index → sala-1 → sala-2 → sala-3 → sala-5 → final. Cambia los enlaces "AVANZAR" en sala-3 para que vayan a sala-5.

**Si quieres aumentar dificultad:** En cada sala, elimina la pista del botón "Necesito una pista" borrando el elemento `.tip-toggle` y `.tip-content`.

---

## SOPORTE TÉCNICO DURANTE EL EVENTO

Si algún equipo reporta un problema técnico, pídeles que:
1. Recarguen la página (F5)
2. Si pierden el progreso: pueden saltar directamente a la sala donde estaban con la URL directa
3. En caso extremo: dales los códigos de salas anteriores para que continúen

---

*OPERATION REWIND · Capgemini Invent · 2026*
